# Note
```
guid: h{nvdu#lW>
notetype: Basic
```

### Tags
```
```

## Front
Transaction commit

## Back
<ul><li>locks all objects in read and write set</li><li>if any objects in the read state are younger than the transaction it is aborted</li><li>otherwise write changes from write set to global memory</li></ul>

