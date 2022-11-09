# AutonomousLearner

## Scope
This repository contains the code implementation of the paper [The Path to Autonomous Learners](https://arxiv.org/abs/2211.02403). The objective is to build a framework that is capable of learning in a more robust way than traditional machine learning and deep learning systems by mimicking human learning more closely. The final system should both be able to reason critically on its existing knowledge and adapt to a new learning framework or environment.

## Use Case
The target system should be a general learner capable of adapting to any domain. The learning pipeline can be leveraged to treat different use cases:
- Specialized Domain Learning
- Referential Ontology Creation
- Autonomous Conversational Agent

## Benchmark
Since the system initiates its learning process from a starting ontology, an intuitive benchmark is to reconstruct the core of an ontology the framework already learned. Metrics can be defined with respect to concepts (nodes) and relationships (edges). More advances metrics like class hierarchy can also be evaluated.