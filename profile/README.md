## 🌱 The Foundation
> Get the basics right.

<details>
<summary>Read More</summary>

#### Core Data Structure
- Regular Data structure
  - Randomized: Quick Sort, Treap, SkipList
  - Misc: List, Stack, Queue, Priority Queue (taken from gods)
  - Sorted: Binary Search Tree
- [Systems Data structure](https://github.com/csorchard/sds)
  - Hash-Based: Probing vs Chaining in Hashmap
    - Approximate: Bloom Filter, Count Min Sketch, HyperLogLog
    - Rebalancing Map: Consistent Hashing, ChordDHT, Range Based Partitioning, Extendable Hashing
    - Hash Functions: Cuckoo Hash, Murmur Hash,
  - Sorted: BTree, Binary Search Tree, Treap,  Red Black Tree, B Epsilon Tree
  - Multi Dimension: KD Tree, Z-Index, Hilbert Curve
  - Sampling: Reservoir Sampling
  - Stream: Sliding window
  - Difference: Merkal Tree
  - Time: Hashed Wheel Timer
- Concurrent Data Structures:
  - Skip List
  - BTree
 
#### Performance engineering tools
- [Performance Analysis](https://github.com/csorchard/perf_analysis)
  - Heap Dump
  - Trace
  - Jmeter, YCSB
  - VRPC (vector clock)
  - Heap View
  - Write Benchmark
  - Lotsaa
  - GC frequency, threshold
  - Git Bisect
  - Explain Analyze
  - OpenTelemetry Trace

#### Advanced Data Structures
- Arena based skip list
- Roaring BitMap
- Zone Map

</details>

## 🌿 The Plant
> Read, Extract components, and Learn the inner workings.

<details>
<summary>Read More</summary>

#### From MatrixOrigin
- [Systems Data Structures Usage](https://github.com/csorchard/sds_use)
  - HyperLogLog: Used to find NDV before writing segment meta header
  - Bloom Filter: Used for fast range scan through blocks
- [MatrixOrigin Join](https://github.com/dborchard/mojoin.git)
  - Hash Map
  - Memory Pool
  - Reservoir Sampling

#### Misc
- Storage Engine: WAL, Btree, CoW Btree, LSM Tree
- Memtable using Skip List

</details>

## 🌳 The Tree
> Pick a favorite storage engine/main memory system and shrink.

<details>
<summary>Read More</summary>

#### Storage Engines
- Dgraph ristretto: 
- Dgraph badger:  Memory allocation part in pkg z.
- BigCache: 

</details>


## 💧 The Resources
> Revisit papers/slides. Build counterexamples. Think like a scientist.

<details>
<summary>Read More</summary>
  
#### Reading
- [Algorithms and Data Structures for Massive Datasets](https://a.co/d/j4aYee9) - BF, `Count-Min` Sketch, HyperLogLog, Reservoir `Sampling`.
- [The Art of Multiprocessor Programming](https://www.amazon.com/Art-Multiprocessor-Programming-Maurice-Herlihy/dp/0123705916): Concurrent Data Structures.

#### Read
- [Advanced Algorithms and Data Structures](https://a.co/d/3tsZk96): BitMap, BloomFilter, LFU, LRU
- [100 Go Mistakes and How to Avoid Them](https://a.co/d/7EAXgLq) - Concurrency patterns, Mechanical sympathy (last 10 chapters).
- [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/)[Incomplete]: Talk about SIMD, CPU Cache, External Memory, Instruction Level Parallelism.

</details>

## 👨‍🌾 Cultivating Knowledge
> Write what you understood. (Maybe later)

<details>
<summary>Read More</summary>

#### Teachings
- [Method for Implementing lock-free shared data structure](https://www.youtube.com/watch?v=MK1ZqqW-9gM) - Coordination Technique, Large Objects


</details>

## 🥭 The Fruit
> Mark your achievements.

<details>
<summary>Read More</summary>

#### Core Implementations
- [Kmeans++ & Elkan's Kmeans](https://github.com/arjunsk/kmeans): Library extracted from MatrixOrigin's IVFFLAT index.

</details>
