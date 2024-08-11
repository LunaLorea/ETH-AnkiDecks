# Note
```
guid: B8P/.Z]+Q`
notetype: Basic
```

### Tags
```
```

## Front
Jarvis Wrap

## Back
funktioniert für Punkte in allgemeiner Lage
<ol><li>wähle startpunkt welcher auf convexer hülle ist (leftmost punkt)
</li><li>find next point such that all other points are on the left of the line going through both points</li><li>repeat untill at the start again
</li></ol><div>\(O(n\cdot h)\) h is the number of points on the conv hull
</div>
