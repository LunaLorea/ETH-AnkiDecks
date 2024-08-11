# Note
```
guid: NH*?MR/EX{
notetype: Obsidian-cloze-code
```

### Tags
```
```

## Text
<blockquote>
  <p><code>ExecutorService</code> methods: {{c1:: <code>submit(Callable<T> || Runnable)</code>}} to start a task's implemented {{c2:: <code>void run()</code> or <code>T call()</code>}} method, which can then {{c3:: <code>exs.submit(t)</code> or <code>t.start()</code>}} to spawn another task and {{c4:: <code>t.get()</code>}} (need to wrap in try/catch block!) to try and obtain the {{c5:: <code>Future<T></code>}} that represents the result of the spawned task <code>t</code>.</p>
</blockquote>

## Extra

