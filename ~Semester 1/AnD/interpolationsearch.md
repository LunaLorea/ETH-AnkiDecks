# Note
```
guid: zRO5!NV9Zx
notetype: Basic
```

### Tags
```
```

## Front
Interpolationsearch

## Back
Complexity on avrage \(O(\log\log n)\) if the array is evenly distribute
In the worst case (if the values are growing exponentially) the runtime is \(O(n)\) and worse than binary search.

It works by istead of using halfing the array it calculates the fraction of the difference from the lowest to the searched values divided by the difference of the lowest to the highest value.
