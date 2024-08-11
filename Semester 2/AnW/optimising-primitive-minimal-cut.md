# Note
```
guid: PN1phWOCV;
notetype: Basic
```

### Tags
```
```

## Front
Optimising primitive minimal cut

## Back
probabillity to fail = \(\frac 2 {n(n-1)}\)
the probabillity of N failuers in a row \(= \left(1-\frac2 {n(n-1)}\right)^N\leq e^{-\frac{2N} {n(n-1)}}\)
if We choose \(N=c\cdot n^2\) we have an algortithm of \(O(n^4)\) with arbitrary small chance of failure.
