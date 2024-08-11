# Note
```
guid: rHatq$NF%*
notetype: Basic
```

### Tags
```
```

## Front
Executer Service


## Back
The Executer service is a library which manages the threadpool for us and we can submit tasks to this service.

<b>Carefull,</b> if we limit the number of threads, then we can get into the position where threads are waiting for results which will never be computed since all threads are occupied.
