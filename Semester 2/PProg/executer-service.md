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
The Executer service is a library which manages the threadpool for us and we can submit tasks to this service. Tasks are either:
- Runnable objects, with method run() which does not return a value
- Callable<T> objects, with method T call() which returns a object of type T
Use .submit(task) to add a task (returns future object)
use .get() on the future object to wait for the thread to finish and get the returns of the tasks. (throws interrupted exception)

<b>Carefull,</b> if we limit the number of threads, then we can get into the position where threads are waiting for results which will never be computed since all threads are occupied.
