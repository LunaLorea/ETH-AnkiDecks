# Note
```
guid: e3jr?|}0=&
notetype: Basic
```

### Tags
```
```

## Front
Happens-before Order

## Back
is constructed by taking the transitive closure of the program order and the synchronizes-with order.
Every read can see either the latest write in the happens-before order, or any other write that is not ordered by HB.
