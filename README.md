# Awesome-Cloud-Optimization


## 📖 Contents
* 📖 [Orchestration and Placement](#Orchestration-and-Placement)
* 📖 [Runtime Optimization](#Runtime-Optimization)

## Orchestration & Placement
<div id="Orchestration-and-Placement"></div>

|Year|Title|Paper|Short Descr.|
|:---:|:---:|:---:|:---:|
|ASLPOS'14|Quasar: Resource-Efficient and QoS-Aware Cluster Management|[Link](https://dl.acm.org/doi/pdf/10.1145/2644865.2541941)| Cluster management system that increases resource utilization under QoS constraints|
|ASPLOS'13|Paragon: QoS-aware scheduling for heterogeneous datacenters|[Link](https://dl.acm.org/doi/pdf/10.1145/2499368.2451125)| DC scheduler that is heterogeneity and interference-aware|

## Runtime Optimization
<div id="Runtime-Optimization"></div>

|Venue|Title|Paper|Short Descr.|
|:---:|:---:|:---:|:---:|
|ASPLOS'23|Erms: Efficient Resource Management for Shared Microservices with SLA Guarantees|[Link](https://dl.acm.org/doi/pdf/10.1145/3567955.3567964)|Guaranteeing SLAs in shared microservice environments. Profiles microservice latency as a piece-wise linear function of the workload, resource usage, and interference and uses resource scaling models to optimally determine latency targets for microservices|
|ATC'23|Nodens: Enabling Resource Efficient and Fast QoS Recovery of Dynamic Microservice Applications in Datacenters|[Link](https://www.usenix.org/system/files/atc23-shi.pdf)| Runtime system that enables fast QoS recovery of dynamic microservices by allocating just-enough excessive resources (cores?) for microservices|
|OSDI'20|FIRM: An Intelligent Fine-grained Resource Management Framework for SLO-Oriented Microservices|[Link](https://www.usenix.org/system/files/osdi20-qiu.pdf)| RL-based control of CPU/LLC/Memory/Network/IO/Replicas for SLO-driven microservices|
|ASPLOS'19|PARTIES: QoS-Aware Resource Partitioning for Multiple Interactive Services|[Link](https://dl.acm.org/doi/pdf/10.1145/3297858.3304005)| QoS-aware resource manager that leverages a set of hardware and software resource partitioning mechanisms to adjust allocations dynamically at runtime|
|PACT'18|Mage: online and interference-aware scheduling for multi-scale heterogeneous systems|[Link](https://dl.acm.org/doi/pdf/10.1145/3243176.3243183)| Mage leverages fast and online data mining to quickly explore the space of application placements, and determine those that minimize interference between co-resident applications.|


## Resource Oversubscription
<div id="Resource-Oversubscription"></div>

|Year|Title|Paper|Short Descr.|
|:---:|:---:|:---:|:---:|
|ASPLOS'25|Coach: Exploiting Temporal Patterns for All-Resource Oversubscription in Cloud Platforms|[Link](https://dl.acm.org/doi/pdf/10.1145/3669940.3707226)| Coach uses long-term predictions and an efficient VM scheduling policy to exploit temporally complementary patterns|

