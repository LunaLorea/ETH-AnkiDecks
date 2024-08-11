# Note
```
guid: I5E3Hlm=Tb
notetype: Basic
```

### Tags
```
```

## Front
Monte Carlo: improve success chance for one sided error

## Back
Let \(A\) be a Monte Carlo algorithm for a decision problem with one-sided error that has a success probability of \(ε\). Let \(0 < δ ≤ 1\) be a real number.

If we repeat \(A\) at least \(N = ε^{−1} \ln δ^{ −1}\) times and answer YES only if every execution of A returned YES, the resulting algorithm will have a success probability of at least \(1 − δ\).
