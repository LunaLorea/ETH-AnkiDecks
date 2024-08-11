# Note
```
guid: vaK}48[4`B
notetype: Basic
```

### Tags
```
```

## Front
Fork/Join Framework

## Back
Tasks are either:
- RecursiveTask<T>
- RecursiveAction
overwrite compute() method for what the thread should do
Spawn new threads using .fork on a task object.
Create a ForkJoinPool and call .invoke() to start the first thread and get back the result.
