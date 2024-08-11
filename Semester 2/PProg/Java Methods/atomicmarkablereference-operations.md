# Note
```
guid: m]0j$+B[=;
notetype: Basic
```

### Tags
```
```

## Front
AtomicMarkableReference methods

## Back
AtomicMarkableReference(V initialRef, boolean initialMark); Creates a new AtomicMarkableReference with the given initial values.

.attemptMark(V expectedReference, boolean newMark); Atomically sets the value of the mark to the given update value if the current reference is == to the expected reference.

.compareAndSet(V expectedReference, V newReference, boolean expectedMark, boolean newMark); Atomically sets the value of both the reference and mark to the given update values if the current reference is == to the expected reference and the current mark is equal to the expected mark.

.get(boolean[] markHolder); Returns the current values of both the reference and the mark.

.getReference(); Returns the current value of the reference.

.isMarked(); Returns the current value of the mark.