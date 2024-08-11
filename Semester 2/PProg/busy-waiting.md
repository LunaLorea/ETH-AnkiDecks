# Note
```
guid: L)`M|5Vm7z
notetype: Basic
```

### Tags
```
```

## Front
<dt>busy waiting</dt>

## Back
<dd>Occurs when a thread busily (actively) waits, e.g. by spinning in a 
loop, for a condition to become true. In the opposite scenario, the 
thread sleeps (i.e. is blocked; in Java: <code>join()</code>, <code>wait()</code>)
 until the condition becomes true. Trade-off: busy waiting uses up CPU 
time, whereas blocking may cause additional context switches.</dd>
