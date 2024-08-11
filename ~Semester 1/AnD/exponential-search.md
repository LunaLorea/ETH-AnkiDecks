# Note
```
guid: e#ww&d@Xv%
notetype: Basic
```

### Tags
```
```

## Front
Exponential Search

## Back
We first try to minimize the array we need to search 
we see if the value is to the left of the position r and start with r=1 we then double r until the value at this position is higher than the value we search or until r is bigger than the size of the array

After this we search the array from 0 to r with binary search this gives us a runtime of \(O(log(p))\) where \(p\) is the position of the searched value. In the worst case this is \(O(\log n)\) so just like binary search but if \(p<<n\) then this algorithm is faster.
