# Note
```
guid: n7$&ACp]BK
notetype: Basic
```

### Tags
```
```

## Front
Das Coupon-Collector-Problem

## Back
Wieviele Coupons muss man kaufen um alle \(n\) Coupons zu haben (angenommen die Wahrscheinlichkeit ist für jeden Coupon dieselbe)
\(X\) zählt die Anzahl käufe bis man alle hat, \(X_i\) die anzahl bis zum nächsten neuen Coupon.
\(X_i\sim Geo(\frac {n-i+1} n)\) 
\(E[X_i] = \frac n {n-i+1}\)

\(X=\sum_{i=1}^n X_i\), 
\(E[X] = n \cdot H_n = n\ln n+ O(n)\)
