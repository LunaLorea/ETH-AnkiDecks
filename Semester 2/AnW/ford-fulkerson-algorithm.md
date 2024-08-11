# Note
```
guid: u>0?CyK7@t
notetype: Basic
```

### Tags
```
```

## Front
Ford-Fulkerson Algorithm

## Back
Finds Maximal Flow by repeating augmenting paths in the residual network.
Guaranteed to terminate with Integer and Rational but not Irrational Flow.

Runtime for Integer Flows: \(O(U\cdot|V|\cdot|E|)\) 
where \(U=max(cap(e))\) and \(val(f)\leq U \cdot |V|\)

any Rational network can be translated into Integer Network by multiplying with largest denominator
