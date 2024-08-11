# Note
```
guid: mnL[M<t,Z/
notetype: Basic
```

### Tags
```
```

## Front
Monte Carlo: improve success chance for two sided error

## Back
Let A be a Monte Carlo algorithm for a decision problem
with two-sided error that has a success probability of \(1/2 + ε\). Let \(0 < δ ≤ 1\)
be a real number.
If we repeat A at least \(N = 4ε^{−2} \ln δ^{−1}\) times and answer with the majority
of results from all executions, the resulting algorithm will have a success
probability of at least \(1 − δ\).
