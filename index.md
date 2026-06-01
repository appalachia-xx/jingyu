---
layout: homepage
---

## About Me

I am a PhD student in the Distributed Computing and Systems group at Chalmers University of Technology.
The reseaerch lies on stream processing with a focus on relaxing the trade-off between memory control and computation cost.

## Projects

- **&#91;Ongoing&#93; Dynamic relaxed window configurations:** Employ Reinforcement Learning (RL) to dynamically tune window parameters -- specifically, window advance and window size -- at runtime to enable the system to actively select optimal parameter configurations in response to variations in input data distribution and fluctuations in the Stream Processing Engines' (SPEs) load.
- **&#91;Ongoing&#93; Scale LLM service resources:** Train and evaluate an RL Agent on real operational data from CPU-hosted LLM services, leveraging the data-collection pipeline already in place within the [Ryax repository](https://github.com/RyaxTech/ryax-engine), with the objective of learning resource allocation policies that dynamically adapt to non-stationary load.
- **Relaxed window reconfiguration:** Define an algorithm that allows stream Aggregates to dynamically adjust their window parameters (such as window size and window advance) during runtime to better align the Aggregate's behavior with the characteristics of the incoming data and current system load.
- **Memory trade-offs in stream Aggregtes:** Evaluate various compression libraries (Snappy, Zstandard, JZlib) and introduce an adaptive mechanism that adjusts compression based on workload, showing performance differences and highlighting the potential of dynamic, low-overhead compression to improve memory efficiency and flexibility in stream analytics.
- **On-demand memory compression:** The RL Agent acts on a live stream Aggregate to adjust its memory compression by applying a given number of compression actions while meeting a specified latency threshold.


{% include_relative _includes/publications.md %}
