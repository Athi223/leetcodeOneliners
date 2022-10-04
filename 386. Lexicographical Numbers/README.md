## 386. Lexicographical Numbers

Given an integer n, return all the numbers in the range [1, n] sorted in lexicographical order.

You must write an algorithm that runs in O(n) time and uses O(1) extra space. 

## Python3

```python
class Solution:
    def lexicalOrder(self, n: int) -> List[int]:	
        return sorted(range(1,n+1),key=str)
```