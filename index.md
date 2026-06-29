---
layout: homepage
---

## About Me

<!-- <div style="text-align: justify" markdown="1"> -->
I am a PhD student in the Distributed Computing and Systems group at Chalmers University of Technology.
My reseaerch lies on stream processing, with a focus on runtime adaptivity of stream Aggregates -- dynamically balancing resource consumption, output performance and correctness guarantees based on evolving workloads and deployment conditions.
<!-- </div> -->

## Projects

<!-- <div style="text-align: justify" markdown="1"> -->
- **&#91;Ongoing&#93; Adaptive window parameter tuning via RL:** Employ Reinforcement Learning (RL) to dynamically tune window advance and window size at runtime to enable the system to actively select optimal configurations in response to variations in input data distribution and fluctuations in the Stream Processing Engine (SPE) load.
- **&#91;Ongoing&#93; Scale LLM service resources:** Train and evaluate an RL-based policy for CPU and memory limit recommendations on real operational data from CPU-hosted LLM services, leveraging the data-collection pipeline already in place within the [Ryax repository](https://github.com/RyaxTech/ryax-engine), with the objective of learning resource allocation policies that dynamically adapt to non-stationary load.
- **Window reconfiguration with correctness guarantees:** Define algorithms that allows stream Aggregates to dynamically adjust their window parameters -- window size and window advance -- during runtime, ensuring reconfiguration correctness while adapting Aggregate behavior to incoming data characteristics and current system load ([paper](https://dl.acm.org/doi/10.1145/3809481.3812621)).
- **On-demand memory compression:** Propose an RL-based approach to dynamically adjust Aggregate memory compression by applying a given number of compression actions while meeting a specified latency threshold ([paper](https://dl.acm.org/doi/10.1145/3676151.3719369)). By evaluating various compression libraries (Snappy, Zstandard, JZlib), we introduce an adaptive mechanism that adjusts compression according to the workload, thereby showing performance differences and highlighting the potential of dynamic, low-overhead compression for improving memory efficiency and flexibility in stream analytics ([paper](https://zenodo.org/records/20466619)).
<!-- </div> -->


{% include_relative _includes/publications.md %}
