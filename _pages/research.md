---
layout: lab
title: "Research"
permalink: /research/
description: "Communication networks, edge computing and AI systems, and quantum information systems: performance analysis, resource allocation, and learning and decision algorithms."
---

Our research spans **communication networks**, **edge computing and AI systems**, and **quantum information systems**. We study how physical constraints, limited resources, and uncertainty affect what systems can achieve and how they should be designed and operated. Mathematical modeling and analysis guide our algorithms; simulation, measurement, and system implementation help us evaluate them.

Three connected questions guide our work across these domains.

## Performance Limits and Trade-offs
{: #limits}

*What is achievable, and what performance can be guaranteed?*

We characterize performance limits and trade-offs in communication, computation, and sensing. Topics include reliability and security, latency and inference accuracy, throughput and power consumption, and the cost of acquiring information. Where the model permits, we derive analytical bounds and algorithmic performance guarantees.

In wireless networks, this includes the effects of interference, mobility, and imperfect channel information on secure and reliable communication. In edge AI systems, we examine how networking and hardware settings shape inference performance and resource use, as in our [deep video analytics]({{ '/publications/#edge-video-analytics' | relative_url }}) and [CORAL]({{ '/publications/#coral' | relative_url }}) studies.

Our quantum information research includes quantum algorithms, the quantum switch, quantum key distribution (QKD), and quantum sensing. We investigate the roles of noise, measurement, and available quantum resources in the performance of these systems.

## Network Design and Resource Allocation
{: #networks}

*How should systems be configured and resources shared?*

In **communication networks**, we study spectrum sharing, interference management, symbiotic radio and backscatter, integrated sensing and communication (ISAC), and UAV and satellite communications. Our work on [secure symbiotic radio]({{ '/publications/#secure-symbiotic-radio' | relative_url }}), for example, connects passive localization with beamforming design. Our [multi-UAV data collection]({{ '/publications/#multi-uav-data-collection' | relative_url }}) research addresses covertness, reliability, and fairness under imperfect channel information.

In **edge computing and AI systems**, we study task offloading, capacity planning, workload placement, and runtime resource management. [Air-ground collaborative offloading]({{ '/publications/#air-ground-offloading' | relative_url }}) connects mobile computing resources with communication networks. This direction also extends to carbon-aware edge computing, including how workloads should be placed and scheduled across devices while accounting for performance, energy use, and carbon emissions.

## Learning and Decision Systems
{: #decisions}

*How should systems act when their environment is not fully known?*

We develop learning and optimization methods for sequential and distributed decisions. Bandit methods, reinforcement learning, game theory, and optimization help us address partial or delayed feedback, changing environments, and coordination among network participants. We also study algorithmic guarantees, including regret bounds that compare cumulative performance with a specified benchmark under explicit assumptions.

Our edge research connects two complementary directions:

- **AI for Edge Computing:** learning-based resource management, offloading decisions, and computing capacity planning, including [multi-agent reinforcement learning for vehicular fog computing]({{ '/publications/#marl-capacity-planning' | relative_url }}).
- **Edge Computing for AI:** communication and computing systems that support efficient AI inference. Examples include adapting video transmission to balance inference accuracy and latency, and tuning device resources to meet throughput and power targets in CORAL.

We examine both the benefit of new information and the communication, computation, and observation effort required to acquire and use it.

---

[Explore our publications]({{ '/publications/' | relative_url }}) · [Join the lab]({{ '/contact/' | relative_url }})
