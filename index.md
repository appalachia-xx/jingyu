---
layout: homepage
---

## About Me

<!-- <div style="text-align: justify" markdown="1"> -->
I am a PhD student in the Distributed Computing and Systems group at Chalmers University of Technology.
My reseaerch lies on stream processing with a focus on relaxing the trade-off between memory control and computation cost.
<!-- </div> -->

## Projects

<!-- <div style="text-align: justify" markdown="1"> -->
- **&#91;Ongoing&#93; Dynamic relaxed window configurations:** Employ Reinforcement Learning (RL) to dynamically tune window parameters -- specifically, window advance and window size -- at runtime to enable the system to actively select optimal parameter configurations in response to variations in input data distribution and fluctuations in the Stream Processing Engines' (SPEs) load.
- **&#91;Ongoing&#93; Scale LLM service resources:** Train and evaluate a RL-based policy for CPU and memory limit recommendations on real operational data from CPU-hosted LLM services, leveraging the data-collection pipeline already in place within the [Ryax repository](https://github.com/RyaxTech/ryax-engine), with the objective of learning resource allocation policies that dynamically adapt to non-stationary load.
- **Relaxed window reconfiguration:** Define an algorithm that allows stream Aggregates to dynamically adjust their window parameters (such as window size and window advance) during runtime to better align the Aggregate's behavior with the characteristics of the incoming data and current system load.
- **On-demand memory compression:** Propose a RL-based approach to dynamically adjust its memory compression by applying a given number of compression actions while meeting a specified latency threshold. Also, by evaluating various compression libraries (Snappy, Zstandard, JZlib) and we introduce an adaptive mechanism that adjusts compression based on workload, showing performance differences and highlighting the potential of dynamic, low-overhead compression to improve memory efficiency and flexibility in stream analytics.
<!-- </div> -->


{% include_relative _includes/publications.md %}
