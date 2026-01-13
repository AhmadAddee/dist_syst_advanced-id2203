# Module 1 - Introduction to Distributed Systems

## L1 - Overview and Intro

This site to be checked out (developed by course teachers): https://datasystems.nu/.

The course relies on 3 systems principles; **performance**, **trust**, and **simplicity**. You want to have a system that performs very well, that's why a Python script is not enough. Trust is also very important, that's the guarantee that your file wont vanish when a Google Drive server burns down somewhere. Simplicity is what makes the system usable, no matter how powerful and well-performed the system is.<br>
<img src="pics/principles.png" alt="pics/principles.png" width=300>

The course topics (basic in red color):
- $\color{red}Intro \ to \ Distributed \ Systems$
- $\color{red}Fundamental \ Abstractions \ and \ Failure \ Detectors$
- $\color{red}Reliable \ and \ Causal \ Order \ Broadcast$
- $\color{red}Consensus \ (Paxos)$
- Replicated State Machines (OmniPaxos, Raft, Zab etc.)
- Distributed Shared Memory & CRDTs
- Real-Time Abstractions (Spanner, Atomic, Quantum clocks)
- Consistent Snapshotting (Data Management)
- Distributed ACID Transactions (Cloud DBs)

### What is a distributed system?
A set of **nodes**, connected by a **network**, which appear to its users as a **single** coherent system. On the other hand, a **_distributed algorithm_** is a copy of a program running in each process.


- Know how to specify the properties of distributed algorithms, so called liveness and safety properties.
