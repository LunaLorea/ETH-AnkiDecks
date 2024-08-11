# Note
```
guid: GEp(qjy]<H
notetype: Basic
```

### Tags
```
```

## Front
Peterson Lock

## Back
1. Set interest flag [array]
2. Set Victim
3. wait till:
    - Other thread has no interest
    - Victim is not you
4. enter critical section
5. release lock

Only for two threads.

A correct implementation would have to utilze AtomicIntegerArray class for the flags.
