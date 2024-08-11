# Note
```
guid: FKngK)&fVy
notetype: Basic
```

### Tags
```
```

## Front
Transaction Memory Timestamps

## Back
Each atomic object has a time stamp when it was last written
each transaction keeps track of when it got 'birthed'.
When reading data, transactions check if the object is in the write set, if not it checks if the object was written to before the transaction got birthed. if not it aborts.

