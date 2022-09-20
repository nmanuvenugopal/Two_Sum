# Two_Sum
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.  You may assume that each input would have exactly one solution, and you may not use the same element twice.  You can return the answer in any order.

# Input: nums = [2,7,11,15], target = 9
# Output: [0,1]
# Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

# Input: nums = [3,2,4], target = 6
# Output: [1,2]

We can implement this by having two for loop.
First loop will run from  0 to length of list -1.
Second loop will run from 1 to length of list.
