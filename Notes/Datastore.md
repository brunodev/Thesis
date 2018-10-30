# Datastore
All read/write operations will be done directly on the object. On every write operation a message will be added to a Queue with the changes to the object. The queue should then be dequeued in a thread safe way to disk.

I need to figure out how to not write the entire object each time