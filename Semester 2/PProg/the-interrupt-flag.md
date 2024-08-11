# Note
```
guid: b$i:1|wAhL
notetype: Basic
```

### Tags
```
```

## Front
The Interrupt flag

## Back
Each thread has a interrupt flag which can be activated by using the .interrupt() method on that thread. This will do nothing unless the interrupted thread polls the flag eg by using .interrupted() on itself.
