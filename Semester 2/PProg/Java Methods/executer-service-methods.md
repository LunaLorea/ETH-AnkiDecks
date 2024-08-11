# Note
```
guid: Ef88.~DQw5
notetype: Basic
```

### Tags
```
```

## Front
Executer Service methods

## Back
<ul><li><pre><code>Executors.newFixedThreadPool(poolSize); creates a new thread pool with and the number of threads are defined by poolSize.</code></pre></li><li><pre>tp.submit(task); adds a task to the thread pool and returns future object.</pre></li><li><pre>pool.execute(); puts the submitted tasks in a state where they can be scheduled.</pre></li><li><pre>.get() on the futureObject to wait for the thread to finish (and get the returned result)</pre></li></ul>
