# 🜂 MurMur# MurMur : A Learning Constellation 🌌
A modular multi-agent reasoning architecture where specialized AI agents collaborate to plan, research, critique, and evolve solutions.
## MurMur Constellation Architecture

```mermaid
graph TD

Core((MurMur Core))

%% Primary cognitive agents
Planner((Planner Agent))
Research((Research Cluster))
Critic((Critic Agent))
Council((Council System))
Memory((Memory))
Evolution((Evolution Engine))

%% Research satellites
Knowledge((Knowledge))
Trend((Trend))
Market((Market))
Tech((Tech))

%% Council satellites
VoteA((Vote A))
VoteB((Vote B))
VoteC((Vote C))

Core --- Planner
Core --- Research
Core --- Critic
Core --- Council
Core --- Memory
Core --- Evolution

Research --- Knowledge
Research --- Trend
Research --- Market
Research --- Tech

Council --- VoteA
Council --- VoteB
Council --- VoteC
```
### A Learning Constellation

Distributed Multi-Agent Intelligence System

<p align="center">

![License](https://img.shields.io/badge/license-MIT-black)
![Agents](https://img.shields.io/badge/agents-10-gold)
![Architecture](https://img.shields.io/badge/architecture-distributed-black)
![Status](https://img.shields.io/badge/status-experimental-gold)

</p>

---

## ✦ Vision

MurMur explores a new paradigm for artificial intelligence.

Instead of relying on a single AI model, MurMur coordinates a **constellation of specialized agents** that collaborate, debate, and synthesize knowledge together.

The goal is to create a **distributed intelligence layer** capable of:

- large-scale research  
- narrative analysis  
- creative systems  
- decision support  

MurMur acts as an orchestration layer connecting AI agents, infrastructure, and knowledge systems.

---

## ✦ MurMur Constellation Architecture

MurMur operates as a **constellation of agents coordinated by an orchestrator**.

Tasks move through a structured pipeline where agents analyze, debate, and synthesize results.

```mermaid
flowchart TB
    U[Human / Founder] --> UI[MurMur Dashboard]

    UI --> ORCH[God Agent / Orchestrator]

    ORCH --> COUNCIL[Constellation Council]

    COUNCIL --> A1[Research Agent]
    COUNCIL --> A2[Pattern Detection Agent]
    COUNCIL --> A3[Narrative Analysis Agent]
    COUNCIL --> A4[Strategy Agent]
    COUNCIL --> A5[Experimental Agent]
    COUNCIL --> A6[Teacher Agent]
    COUNCIL --> A7[Reflective Agent]

    A1 --> QUEUE[Supabase Job Queue]
    A2 --> QUEUE
    A3 --> QUEUE
    A4 --> QUEUE
    A5 --> QUEUE
    A6 --> QUEUE
    A7 --> QUEUE

    QUEUE --> WORKERS[Workers / Executors]

    WORKERS --> MEMORY[Knowledge Store]
    WORKERS --> OUTPUT[Results]

    MEMORY --> ORCH
    OUTPUT --> UI
