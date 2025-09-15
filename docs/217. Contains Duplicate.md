The proble is [here](https://leetcode.com/problems/contains-duplicate/description/)

Python

```python
from typing import List

def containsDuplicate(nums: List[int]) -> bool:

    temp = []

    for num in nums:
        if num not in temp:
            temp.append(num)
        else: return True
    
    return False

def containsDuplicate2(nums: List[int]) -> bool:

    return nums != list(set(nums))

if __name__ == '__main__':

    nums = [1,2,3,4]
    #nums = [1,2,3,1]
    #nums = [1,1,1,3,3,4,3,2,4,2]

    print(containsDuplicate(nums))
    print(containsDuplicate2(nums))
