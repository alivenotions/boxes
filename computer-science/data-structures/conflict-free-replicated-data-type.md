# Conflict-free Replicated Data Type

* A data structure that is replicated over multiple nodes and can be updated independently and concurrently and merged sometime in the future.
* The data structure ensures that the merges will be conflict-free.
* CRDTs aim for eventual consistency in distributed systems.
* There are two types of CRDTs. The operation CRDT which ensures that only the changed operation is relayed and merged. But for this the packets shouldn't be lost and the ordering of events should be maintained.
* The second type is state CRDT which requires the complete state to be relayed. This requires a larger payload.

### Links

* [https://en.wikipedia.org/wiki/Conflict-free\_replicated\_data\_type](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)

