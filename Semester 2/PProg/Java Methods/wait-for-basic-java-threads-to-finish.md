# Note
```
guid: C:.7g>{bhb
notetype: Basic
```

### Tags
```
```

## Front
Wait for basic Java threads to finish


## Back
After creating the thread objects and starting the threads, use the <b>.join() </b>method on all threads, which will make the current thread wait untill that thread has terminated.
The join() method can throw an <b>InterruptedException </b>which is why we need to wrap this method in a try catch block.
