# DataSys

DataSys builds open-source data management and processing systems for continuously evolving data.

Our work spans stream processing, dynamic graph systems, vector search and indexing, online data maintenance, and reproducible data-system benchmarks.

Website: [datasys.sage.org.ai](https://datasys.sage.org.ai/)

## Ecosystem

- [IntelliStream](https://github.com/intellistream) incubates early research ideas.
- **DataSys** develops framework-neutral data systems and benchmarks.
- [RIDE Lab](https://github.com/RIDE-Lab) conducts agent-native systems research and stewards the core repositories of [SAGE](https://github.com/RIDE-Lab/SAGE).
- **SAGE — Streaming-Augmented Generative Execution — is the ecosystem's shared flagship product.** It applies streaming-computing ideas to LLM inference and agent execution, integrating DataSys capabilities for evolving data, retrieval, and state; [Sage Mate](https://github.com/RIDE-Lab/sage-mate) is an application built with SAGE.
- [vLLM-HUST](https://github.com/vLLM-HUST) is the independent inference substrate for model execution, scheduling, compilation, kernels, and hardware acceleration. RIDE Lab systems call it rather than owning it as an internal layer.

## Projects

### Stream Processing

- [MorphStream](https://github.com/DataSysResearch/MorphStream) - transactional stream-processing engine for ACID transactions over streaming data.
- [BriskFlow](https://github.com/DataSysResearch/BriskFlow) - vector-native stream processing engine for join-backed semantic windows and continuously evolving data.

### Achievements

- [Complete publication timeline](https://datasys.sage.org.ai/achievements.html) -
  papers, demos, authors, DOI records, official acceptance evidence, and
  corresponding DataSys repositories.
- [CANDOR-Bench](https://doi.org/10.1145/3786630) - SIGMOD 2026 continuous
  ANNS benchmark for dynamic open-world streams.
- [StreamFP](https://doi.org/10.1145/3774904.3792584) - WWW 2026
  fingerprint-guided data selection for efficient stream learning.
- [GRACE](https://icde2026.github.io/accepted-papers.html) - accepted ICDE
  2026 work on reconstruction cost in dynamic graph processing.
- [BriskSnapshot](https://datasys.sage.org.ai/achievements.html) - join-backed semantic windows demonstration reported by its authors as accepted to the ICPP 2026 demo track; the public conference record is pending.

### Dynamic Graphs

- [GRACE](https://github.com/DataSysResearch/GRACE) - dynamic graph processing for continuously evolving graph data.

### Vector Search and ANNS

- [CANDOR-Bench](https://github.com/DataSysResearch/CANDOR-Bench) - continuous ANNS evaluation under dynamic, open-world streams.
- [vasg](https://github.com/DataSysResearch/vasg) - DataSys-maintained VSAG derivative used by CANDOR-Bench for reproducible vector-index evaluation.

### Streaming Data Analysis

- [Sesame](https://github.com/DataSysResearch/Sesame) - data-stream clustering system and benchmark.

### Approximate Computing

- [AMM-Algorithms](https://github.com/DataSysResearch/AMM-Algorithms) - framework-neutral C++ implementations of approximate matrix multiplication algorithms with Python bindings.
- [LibAMM](https://github.com/DataSysResearch/LibAMM) - reproducible benchmark suite for approximate matrix multiplication systems.

### Supporting Systems

- [AllianceDB](https://github.com/DataSysResearch/AllianceDB)
- [CStream](https://github.com/DataSysResearch/CStream)
- [PECJ](https://github.com/DataSysResearch/PECJ)
- [PDSC](https://github.com/DataSysResearch/PDSC)
- [SentiStream](https://github.com/DataSysResearch/SentiStream)
- [StreamFP](https://github.com/DataSysResearch/StreamFP)
- [SRTFD](https://github.com/DataSysResearch/SRTFD)

### Benchmarks and Research Resources

- [CFInjectBench](https://github.com/DataSysResearch/CFInjectBench)
- [CC-bench-tools](https://github.com/DataSysResearch/CC-bench-tools)
- [StreamProcessing Reading List](https://github.com/DataSysResearch/StreamProcessing_ReadingList)
- [Parallel and Distributed State Management Survey](https://github.com/DataSysResearch/parallel-distributed-state-management-survey)

### ANNS Baseline Forks

These repositories preserve upstream algorithms and benchmark baselines used in DataSys evaluation. DataSys ownership does not replace or imply authorship of the upstream projects.

- [Parlay-HNSW](https://github.com/DataSysResearch/Parlay-HNSW) - ParlayANN-derived HNSW concurrency baseline.
- [Concurrent-HNSW](https://github.com/DataSysResearch/Concurrent-HNSW) - concurrent HNSW evaluation baseline in the hnswlib fork network.
- [hnswlib](https://github.com/DataSysResearch/hnswlib) - pinned hnswlib baseline snapshot.
- [cufe](https://github.com/DataSysResearch/cufe) - DiskANN-network research fork used by CANDOR-Bench.
- [IP-DiskANN](https://github.com/DataSysResearch/IP-DiskANN) - pinned CANDOR-Bench IP-DiskANN baseline.
- [big-ann-benchmarks](https://github.com/DataSysResearch/big-ann-benchmarks) - billion-scale ANNS benchmark fork.

## Project Graduation

Projects graduate from IntelliStream when they have a clear public abstraction, named maintainers, reproducible evaluation, documentation, tests, licensing, and a sustainable release path.

DataSys is not a catch-all state-management umbrella. It owns framework-neutral data systems, indexes, benchmarks, and data lifecycle infrastructure.

See our [contribution guide](https://github.com/DataSysResearch/.github/blob/main/CONTRIBUTING.md), [security policy](https://github.com/DataSysResearch/.github/blob/main/SECURITY.md), and [support guide](https://github.com/DataSysResearch/.github/blob/main/SUPPORT.md).
