# Sliding Window
# Fixed Sliding window
Imaging two shape
- Rectangle
    - It can represent array
    - It can represent linked list
    - It can represent any arbitrary sequence of data
    ![](assets/rectangle.png)
- Window
    - Subset of array
    - Ask questions
    - Optimize as per question
    - Is this the best I can do?
    - Slide the window over once it is solved for given window subset
    - Test soln in new window and check if this is better subset
    - Keep sliding until best is found
    ![](assets/sliding-window.png)
This is called fixed sliding window technique.

# Dynamically resizable sliding window
- Window size is growing based on criteria
- It does shrink from left as per problem otimization
- It keeps growing/shrinking
- Eventually it grows to the point at the end of the array
Based on different type of problem we either choose fixed size dynamic window or dynamic size sliding window.
# Abstracting The native brute force approach
- Start the index
- enumurate all possible scope
- This duplicate works
![](assets/brute-force.png)
- Optimized sliding window, we get rid of duplicate work
    - Slide over linear time
    - Substract result for the elements no more in sliding window
    - Add data to result based on new sliding window
# Maximum sum of a contiguous subarray of size 3
![](assets/maximum-subarray-1.png)
![](assets/maximum-subarray-2.png)
# How to recognize this pattern?
- Suitable for iterable sequentially
- Related to contiguous sequence of elements
- Good with
    - string
    - array
    - linked list
- Related to 
    - minimum of something
    - maximum of something
    - longest 
    - shortest
    - contains 
    - calculate something for example sum, average etc
# Questions Variants
## Fixed length window size
https://www.educative.io/courses/grokking-the-coding-interview/JPKr0kqLGNP

## Dynamic window size
https://leetcode.com/problems/minimum-size-subarray-sum/
https://leetcode.com/problems/max-consecutive-ones
https://leetcode.com/problems/max-consecutive-ones-ii/
https://leetcode.com/problems/max-consecutive-ones-iii/
https://leetcode.com/problems/remove-duplicates-from-sorted-array/
https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/
https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/

## Dynamic window size with auxillary data structure
https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/
https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/
https://leetcode.com/problems/consecutive-characters/
https://leetcode.com/problems/longest-repeating-character-replacement/

## Multiple Dynamic window
https://leetcode.com/problems/subarrays-with-k-different-integers/

## Multi dimensional window
https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/

## Sounds similar but not a sliding window problem due to additive nature
https://leetcode.com/problems/subarray-sum-equals-k/
https://leetcode.com/problems/maximum-subarray/

# Commonalities 
- Everything is grouped sequentially
- Longest/smallest/contains/max/min
- 




# Reference 
https://www.youtube.com/watch?v=MK-NZ4hN7rs