## Data Structures

#### Concurrent
- Red Black Tree
- Roaring BitMap
- HashMap
- Arena based skip list


#### Storage Engine
- BTree
- CoW Btree
- Wal
- LSM Tree
- Memtable using Skip List
- Merkal Tree
- B Epsilon Tree
- K-D tree
- Z-Index: storage optimization

#### Hashing
- Consistent Hashing:
- Range Partitioning
- Hash Index: In database, CXL
- Cuckoo Hash

#### Approximate (to organize into hashing, filter, etc)
- Bloom Filter
- Count Min Sketch
- Cuckoo filter
- HyperLogLog
- Zone Map
- Reservoir Sampling
- Sliding window

#### Distributed Systems
- Consistent Hash
- Hash Wheel Timer

  
## Misc Items
- Mpool
- Off Heap Cache
- Vector
- Basics (all in one + leet code + algorithms etc)

## Data Structures Usage in Real-World Projects
- HyperLogLog: ApproxCount SQL Function
- Count Min Sketch: Frequency Estimation Optimizer

#### Reading
- [Algorithms and Data Structures for Massive Datasets](https://a.co/d/j4aYee9) - BF, `Count-Min` Sketch, HyperLogLog, Reservoir `Sampling`.
- [The Art of Multiprocessor Programming](https://www.amazon.com/Art-Multiprocessor-Programming-Maurice-Herlihy/dp/0123705916)

#### Read
- [Advanced Algorithms and Data Structures](https://a.co/d/3tsZk96): BitMap, BloomFilter, LFU, LRU
- [100 Go Mistakes and How to Avoid Them](https://a.co/d/7EAXgLq) - Good book for concurrency patterns and refreshing mechanical sympathy (last 10 chapters).
- [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/)[Partially read]: Talk about SIMD, CPU Cache, External Memory, Instruction Level Parallelism.

