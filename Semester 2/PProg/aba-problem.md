# Note
```
guid: JzCN}HTY4u
notetype: Basic
```

### Tags
```
```

## Front
ABA Problem

## Back
Can occure when a change is not correctily recognised and therefore the program proceeds as if no changes occured.

Example:
In A Stack we have a, b, ..... and we pop a so we want to set b as head and check if a is still head.
Meanwhile the stack got changed to a, c, .. by another thread.
we don't see the change when checking if a is still head, but b is not in the stack anymore so setting it as head would lead to errors.
