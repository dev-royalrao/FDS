# FDS
Fundamentals of Distributed Systems Assignment-1

🚀Implemented two distributed systems using Python and Docker:

1. Vector Clock Key-Value Store: Ensures causal consistency with vector clocks and message buffering.

2. Smart Grid Load Balancer: Dynamically routes EV charging load using Prometheus & Grafana.


🔁 Part 1: Vector Clock Key-Value Store
A distributed key-value store implemented in Python that maintains causal consistency using vector clocks. Each node tracks logical time and ensures that dependent events are delivered in the correct order across the system. Out-of-order messages are buffered until their causal dependencies are met.

✅ Features:

Vector clock-based causal ordering

Message buffering and delayed delivery

RESTful API for reads/writes

Dockerized 3-node system with client testing interface

Demonstrates correctness through a causal test scenario

⚡ Part 2: Smart Grid Dynamic Load Balancer
A Python-based distributed system that simulates a smart grid for balancing electric vehicle (EV) charging requests across multiple substations. The system monitors real-time load using Prometheus and intelligently routes requests to the least-loaded substation using a custom load balancer.

✅ Features:

Microservices for charging, balancing, and substations

Real-time load metrics exposed via /metrics

Monitoring with Prometheus + Grafana dashboards

Load tested under simulated "rush hour" scenarios

Fully containerized using Docker Compose


👨‍🎓 Submitted by: Royal Rao (G4AI2016)
