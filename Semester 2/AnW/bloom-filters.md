# Note
```
guid: y=Ztr@ODF`
notetype: Basic
```

### Tags
```
```

## Front
bloom filters

## Back
store boolean values for each key.
run the key through all hash functions and turn the array at all resulting indices to 1. When looking up we check if all entries are 1 to determin if the boolean for the key is 1.
