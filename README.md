## Pattern: Sliding Window

* https://leetcode.com/problems/maximum-subarray/ # Close enough
* https://leetcode.com/problems/minimum-size-subarray-sum/
* https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/
* https://leetcode.com/problems/fruit-into-baskets/
* https://leetcode.com/problems/longest-substring-without-repeating-characters/
* https://leetcode.com/problems/longest-repeating-character-replacement/
* https://leetcode.com/problems/max-consecutive-ones-iii/
* https://leetcode.com/problems/permutation-in-string/
* https://leetcode.com/problems/find-all-anagrams-in-a-string/
* https://leetcode.com/problems/minimum-window-substring/
* https://leetcode.com/problems/substring-with-concatenation-of-all-words/

## Pattern: Two Pointers

* https://leetcode.com/problems/two-sum/
* https://leetcode.com/problems/remove-duplicates-from-sorted-array/
* https://leetcode.com/problems/squares-of-a-sorted-array/
* https://leetcode.com/problems/3sum/
* https://leetcode.com/problems/3sum-closest/
* https://leetcode.com/problems/3sum-smaller/
* https://leetcode.com/problems/subarray-product-less-than-k/
* https://leetcode.com/problems/sort-colors/
* https://leetcode.com/problems/4sum/
* https://leetcode.com/problems/backspace-string-compare/
* https://leetcode.com/problems/shortest-unsorted-continuous-subarray/

## Pattern: Fast & Slow pointers
* https://leetcode.com/problems/linked-list-cycle/
* https://leetcode.com/problems/linked-list-cycle-ii/
* https://leetcode.com/problems/happy-number/
* https://leetcode.com/problems/middle-of-the-linked-list/
* https://leetcode.com/problems/palindrome-linked-list/
* https://leetcode.com/problems/reorder-list/
* https://leetcode.com/problems/circular-array-loop/

## Pattern: Merge Intervals
* https://leetcode.com/problems/merge-intervals/
* https://leetcode.com/problems/insert-interval/
* https://leetcode.com/problems/interval-list-intersections/
* https://leetcode.com/problems/meeting-rooms-ii/
* Could not find equivalent. Given a list of intervals with values, find the peak sum (i.e. if intervals are overlapping, sum their values)
* https://leetcode.com/problems/employee-free-time/

## Pattern: Cyclic Sort

* Couldn't find equivalent for the first question. The second question below encompasses the first one though. See https://leetcode.com/problems/missing-number/discuss/859510/C%2B%2B-O(N)-O(1)-using-Cyclic-Sort for how grokking the coding interview approached these problems. It uses the fact that we can sort the array in O(n) without comparison operators
* https://leetcode.com/problems/missing-number/
* https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/
* https://leetcode.com/problems/find-all-duplicates-in-an-array/
* combine https://leetcode.com/problems/find-the-duplicate-number/ and https://leetcode.com/problems/missing-number/
* https://leetcode.com/problems/first-missing-positive/
* https://leetcode.com/problems/kth-missing-positive-number/

## Pattern: In-place Reversal of a LinkedList
* https://leetcode.com/problems/reverse-linked-list/
* https://leetcode.com/problems/reverse-linked-list-ii/
* https://leetcode.com/problems/reverse-nodes-in-k-group/
* Next question is the same, but alternate each subgroup
* https://leetcode.com/problems/rotate-list/

## Pattern: Tree Breadth First Search
* https://leetcode.com/problems/binary-tree-level-order-traversal/
* https://leetcode.com/problems/binary-tree-level-order-traversal-ii/
* https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/
* https://leetcode.com/problems/minimum-depth-of-binary-tree/
* https://leetcode.com/problems/inorder-successor-in-bst/  # Close, not exact
* https://leetcode.com/problems/populating-next-right-pointers-in-each-node/  # Close, grokk assumes non-perfect tree
* Next question is the same, but connect end nodes to the next level instead of null
* https://leetcode.com/problems/binary-tree-right-side-view/

## Pattern: Tree Depth First Search
* https://leetcode.com/problems/path-sum/
* https://leetcode.com/problems/path-sum-ii/
* https://leetcode.com/problems/sum-root-to-leaf-numbers/
* https://leetcode.com/problems/check-if-a-string-is-a-valid-sequence-from-root-to-leaves-path-in-a-binary-tree/description/
* https://leetcode.com/problems/path-sum-iii/
* https://leetcode.com/problems/diameter-of-binary-tree/
* https://leetcode.com/problems/binary-tree-maximum-path-sum/

## Pattern: Two Heaps
* https://leetcode.com/problems/find-median-from-data-stream/
* https://leetcode.com/problems/sliding-window-median/
* https://leetcode.com/problems/ipo/
* https://leetcode.com/problems/find-right-interval/

## Pattern: Subsets
* https://leetcode.com/problems/subsets/
* https://leetcode.com/problems/subsets-ii/
* https://leetcode.com/problems/permutations/
* https://leetcode.com/problems/letter-case-permutation/
* https://leetcode.com/problems/generate-parentheses/
* https://leetcode.com/problems/generalized-abbreviation/
* https://leetcode.com/problems/different-ways-to-add-parentheses/
* https://leetcode.com/problems/unique-binary-search-trees-ii/
* https://leetcode.com/problems/unique-binary-search-trees/

## Pattern: Modified Binary Search
* https://leetcode.com/problems/binary-search/  # Close enough. The grokking problem allows sorted input arrays as ascending or descending, which only introduces a simple check
* Did not find. Problem is find index of smallest element greater or equal to input value
* https://leetcode.com/problems/find-smallest-letter-greater-than-target/
* https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/
* https://leetcode.com/problems/search-in-a-sorted-array-of-unknown-size/
* https://leetcode.com/problems/find-k-closest-elements/ (with K == 1)
* https://leetcode.com/problems/peak-index-in-a-mountain-array/
* https://leetcode.com/problems/find-in-mountain-array/
* https://leetcode.com/problems/search-in-rotated-sorted-array/
* Similar to previous, but find the number of rotations of the array.

## Pattern: Bitwise XOR
* https://leetcode.com/problems/single-number/
* https://leetcode.com/problems/single-number-iii/
* https://leetcode.com/problems/complement-of-base-10-integer/
* https://leetcode.com/problems/flipping-an-image/

## Pattern: Top 'K' elements
* Same as second question, but the first Grokking question wants the top K instead of the bottom K
* https://leetcode.com/problems/kth-largest-element-in-an-array
* https://leetcode.com/problems/k-closest-points-to-origin/
* https://leetcode.com/problems/minimum-cost-to-connect-sticks/
* https://leetcode.com/problems/top-k-frequent-elements/
* https://leetcode.com/problems/sort-characters-by-frequency/
* https://leetcode.com/problems/kth-largest-element-in-a-stream/
* https://leetcode.com/problems/find-k-closest-elements/
* https://leetcode.com/problems/least-number-of-unique-integers-after-k-removals/ closest leetcode or https://www.geeksforgeeks.org/maximum-distinct-elements-removing-k-elements/ for exact
* https://www.geeksforgeeks.org/sum-elements-k1th-k2th-smallest-elements/ no leetcode equivalent found
* https://leetcode.com/problems/reorganize-string/
* https://leetcode.com/problems/rearrange-string-k-distance-apart/
* https://leetcode.com/problems/task-scheduler/
* https://leetcode.com/problems/maximum-frequency-stack/

## Pattern: K-way merge
* https://leetcode.com/problems/merge-k-sorted-lists/
* Same as previous, but return the Kth smallest number
* https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/
* https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/
* https://leetcode.com/problems/find-k-pairs-with-smallest-sums/ small difference, grokking has different sort order and wants the largest

## Pattern: 0/1 Knapsack
* https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/RM1BDv71V60
* https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/3jEPRo5PDvx or https://leetcode.com/problems/partition-equal-subset-sum/
* https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/3j64vRY6JnR
* https://leetcode.com/problems/last-stone-weight-ii/ similar concept, but problem description is more abstract.
* https://leetcode.com/problems/combination-sum-ii/ similar, but return the number of combinations instead of the combinations
* https://leetcode.com/problems/target-sum/
* BONUS : Not in grokking, but I still found this very useful https://leetcode.com/problems/ones-and-zeroes/

## Pattern: Topological Sort
* First problem is identical to the following three
* https://leetcode.com/problems/course-schedule/
* https://leetcode.com/problems/course-schedule-ii/ 
* Same as above, but return all instead of any
* https://leetcode.com/problems/alien-dictionary/
* https://leetcode.com/problems/sequence-reconstruction/description/
* https://leetcode.com/problems/minimum-height-trees/

## Misc
* https://leetcode.com/problems/kth-largest-element-in-an-array/
