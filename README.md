# Raft + Distributed Key-Value Store Learning Project (MIT 6.5840)

This repository documents my hands-on learning journey through the Raft consensus algorithm and the distributed key-value store built on top of it, following the structure of the MIT 6.5840 distributed systems course. The goal of this project is to develop a practical understanding of fault tolerance, log replication, leader election, and consistency in distributed systems — and to extend that knowledge into an operational key-value store.

---

## Why This Project Matters
Distributed systems reliability has become foundational in modern backend platforms. By implementing Raft and later a fault-tolerant KV store, this project demonstrates:

- Strong grounding in **consensus algorithms**
- Ability to reason about **consistency and replication**
- Understanding of **quorum-based decision making**
- Practical exposure to **state machine application**
- Progression toward **real-world distributed storage concepts**

This blend of theory + implementation is showcased here as part of my engineering portfolio.

---

## Current Progress

### ✅ Completed
- Course framework setup
- Raft log structure exploration
- Leader election mechanics understanding
- Term and index consistency rules study

### 🟡 In Progress
- Implementing Raft core logic
- AppendEntries handling and log matching
- Commit rules and majority agreement

### 🔜 Coming Next (Portfolio Milestones)
- Persistent state storage
- Snapshotting
- Client request handling over Raft
- Distributed Key-Value Store (Lab)
- Sharded KV with reconfiguration

---

## What This Repo Will Eventually Demonstrate
✅ Raft leader election  
✅ Log replication with consistency guarantees  
✅ Fault-tolerance via majority quorum  
✅ Linearizable client operations  
✅ A replicated distributed KV store  
✅ Sharded KV with dynamic rebalancing  

---

## Learning Objectives
This project is designed to strengthen:

### 🧠 Technical Depth
- distributed coordination
- replication models
- consensus guarantees
- state machine safety

### 🏗 Engineering Ability
- implementing complex protocols
- debugging distributed behavior
- reasoning about failure modes

### 🎯 Practical Outcomes
- stronger backend/system design foundations
- relevant skills for SDE / infra / distributed systems roles
- demonstrable portfolio artifacts

---

## Tech Stack
- **Language:** Go
- **Model:** Raft consensus
- **Extensions:** Key-value store replication
- **Course Reference:** MIT 6.5840 (formerly 6.824)

---

## Future Showcase Additions (optional but recommended)
📌 Animated leader election demo  
📌 Log replication visualization  
📌 Benchmark graphs  
📌 Failure-injection scenarios  
📌 System design write-up section  

---

## Personal Notes
This repository is not a claim of authorship of the original course framework.  
It represents my progressive work, experimentation, and understanding built on top of it.
