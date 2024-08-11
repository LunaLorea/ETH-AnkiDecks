# Note
```
guid: xYH75GcR01
notetype: Basic
```

### Tags
```
```

## Front
Create Orthonormal Basis from eg. Columnspace

## Back
To create a orthonormal basis take the first vector and divide by its length. For each other vector take the dot product with the previous vectors and multiply with said vector and subtract from current vector. now we have a orthogonal vector to each previous vector now divide by its length to get the a normal vector.

\(v'_k={v-\sum\limits_{i=1}^{k-1}(v'_i\cdot v_k) {v'_i\over ||v'_i||^2}\over ||v-\sum\limits_{i=1}^{k-1}(v'_i\cdot v_k) {v'_i\over ||v'_i||^2}||}\)
