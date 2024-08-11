# Note
```
guid: KV=(cqMb<5
notetype: Basic
```

### Tags
```
```

## Front
Artikulationsknoten effizient finden

## Back
1. DFS auf den Graph, speicher reihenfolgen index dfs[v]
2. DP um für jeden knoten denjenigen anderen knoten zu finden der über den DFS tree plus höchstens einer anderen kante am ende. speichern als low[v]
3. v ist ein AK falls:
- v der startknoten des DFS ist und \(degree(v)\geq2\) im DFS Baum hat
- v nicht der startknoten ist falls \(\exists u\in V: (v,u)\in E(T): low[u]\geq dfs[v]\)
4. \((u,v)\) ist eine Brücke falls (check for both directions bc the DFS Tree is directed):
- \((u,v)\in E(T) \land low[v]>dfs[u]\)
