# Docker  

## Problem it Solves: Environment Replication  

**“My code is working on my machine but not on yours.”**  

This is one of the most common concerns developers face when shipping code to production.  

**Reason:** Environment replication. The dependencies, libraries, and their versions installed on a developer’s machine may not exist on another machine. It’s not practical to ask people every time to download and configure all the required components.  

**Here comes Docker** — it wraps all the dependencies, libraries, and configurations needed to run the application inside a container.  

---

## Difference Between Virtualization and Containers  

- **Containers**: Think of them like VMs but without the overhead of a full operating system. They share the host OS kernel, which makes them lightweight and ideal for microservices.  

- **Virtualization**: Refers to logically dividing a physical server into multiple virtual machines, each running its own full operating system.  

---

