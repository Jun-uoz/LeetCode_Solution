```python
class Solution:
    def isPowerOfTwo(self, n: int) -> bool:
        List = []
        i = 0
        while 2 ** i <= n:
            List.append(2 ** i)
            i += 1
        return (n in List)
```
