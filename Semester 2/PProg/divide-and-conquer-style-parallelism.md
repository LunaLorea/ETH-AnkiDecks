# Note
```
guid: iJ81K$4Trw
notetype: Basic
```

### Tags
```
```

## Front
<dt>divide and conquer style parallelism</dt>

## Back
<dd>Also called recursive splitting. Solve a problem in divide and 
conquer style: solve a larger problem by recursively solving smaller 
sub-problems and combine their results. Solve the sub-problems in 
separate threads to gain a speedup. This way, work can be decomposed 
recursively to small tasks that can be efficiently scheduled on 
available tasks using e.g. the ForkJoin framework.</dd>
