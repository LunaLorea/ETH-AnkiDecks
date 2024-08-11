# Note
```
guid: D0;=2xIMx8
notetype: Basic
```

### Tags
```
```

## Front
Local Repair

## Back
find convex hull by repairing a polygon
<ol><li>sort points by ascending x</li><li>connect points to form polygon whichs boarder goes along the ordered points and back</li><li>we move from first to last point, everytime a tripple of points have the last point be to the right we remove the middle point and check again for possible new right turns</li><li>repeat in opposit direction</li></ol>
