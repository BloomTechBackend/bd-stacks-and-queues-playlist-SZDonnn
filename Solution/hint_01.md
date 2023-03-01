There's one edge case you'll need to think about. If you try to `remove()`
an item from the `Queue` when it is empty, you'll get a `NoSuchElementException`.
In `getNextSong()`, see if there's a method that removes and returns the
head of the queue, but returns `null` instead of throwing an exception if
the queue is empty. (Hint: We mention it once in the reading, but you'll
also be able to find it via the [Queue interface javadoc](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html) !)
