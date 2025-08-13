# leetcode-contains-duplicate
My first LeetCode solution: Contains Duplicate problem in Python.
**Language:** Python  
**Difficulty:** Easy  

## Code
class Solution:
    def containsDuplicate(self, nums: List[int]) -> bool:
        s=set()
        for num in nums:
            if num in s:
                return True
            s.add(num)
        return False
