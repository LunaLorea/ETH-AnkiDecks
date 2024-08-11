# Note
```
guid: cDW<lnW$;v
notetype: Basic
```

### Tags
```
```

## Front
Dataflow Programming Model

## Back
Instead of creating a bunch of threads that somehow communicate with each other, we create explicit primitive threads which are structured in a task graph (DAG). Where every thread only starts its execution when all preceding threads terminated and all threads are joined back together in the end.
