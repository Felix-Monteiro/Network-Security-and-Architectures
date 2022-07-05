# Network Security and Architectures
These projects were done in the Advanced Network Security and Architectures course. The primary purpose was to study the principles and techniques for designing and managing secure network infrastructures in isolated environments using GNS3.

### Grades:

* **Project 1:** 18/20
* **Project 2:** 19/20
* **Project 3:** 20/20
------------------------------
## Table of Contents
- [Network Attacks & Countermeasures](#project-1-network-attacks-&-countermeasures)
- [Firewalls](#project-1-firewalls)
- [AAA](#project-1-aaa)
- [IPSec & VPNs](#project-2-ipsec-&-vpns)
- [Networking of virtual containers](#project-2-networking-of-virtual-containers)
- [Kubernetes & Docker Swarm](#project-3-kubernetes-&-docker-swarm)

------------------------------
## Project 1 Network Attacks & Countermeasures
**Report:** [`Network Attacks & Mitigations`](Project_1.pdf)

**Pages:** 1-41

**Config File:** Configurations inside the report in Annex 

This report discusses some network vulnerabilities and countermeasures. It also explains the steps to reproduce such attacks, the steps to prevent them, and some theoretical concepts necessary for understanding them.

### Topics:
* CAM table overflow
* DHCP Spoofing
* ARP poisoning (MitM)
* Root Bridge spoofing (MitM)
* DNS spoofing
* RIP poisoning
* DNS spoofing using DHCP spoofing

------------------------------
## Project 1 Firewalls
**Report:** [`Firewalls`](Project_1.pdf)

**Pages:** 41-68

**Config File:** Configurations inside the report in Annex

This project discusses Firewalls architectures and types. With further investigation regarding Firewalls in campus networks, ZBPF versus classical firewalls and their influence on DoS attacks.

### Topics:
* Classical firewalls versus Zone-Based Policy Firewalls
* Protecting a campus network using a ZBPF
* Defence against DoS attacks

------------------------------
## Project 1 AAA
**Report:** [`AAA`](Project_1.pdf)

**Pages:** 68-82

**Config File:** Configurations inside the report in Annex

This project discusses AAA, which stands for Authentication, Authorization and Accounting (basically, it is a framework used to control who is permitted to use the network resources - authentication - what they are authorized to do - authorization - and capture the actions performed while accessing the network - accounting).

### Topics:
* AAA with TACACS+
* 802.1X Authentication

------------------------------
## Project 2 IPSec & VPNs
**Report:** [`IPSec & VPNs`](Project_2.pdf)

**Pages:** 6-41

**Config File:** Configurations inside the report in Annex

This project discusses IPSec and VPNs, where it is analyzed different VPNs and their configurations.

### Topics:
* IPSec using ESP in tunnel mode
* IPSec with digital certificates and certificate authority
* IPSec with NAT traversal
* GRE over IPSec
* DMVPN Phase 3
* DMVPN over IPSec


------------------------------
## Project 2 Networking of virtual containers
**Report:** [`Networking of virtual containers`](Project_2.pdf)

**Pages:** 41-56

**Config File:** Configurations inside the report in Annex

This project discusses the networking of virtual containers, covering Linux network namespaces, Docker, and Docker Swarm.

### Topics:
* Connecting network namespaces to external networks
* Macvlan networks with VLANs
* Linux VxLAN with multicast routing
* Docker Swarm without data encryption
* Docker Swarm with data encryption

------------------------------
## Project 3 Kubernetes & Docker Swarm
**Report:** [`Kubernetes & Docker Swarm`](Project_3.pdf)

**Config File:** Configurations inside the report in Annex

This project discusses Kubernetes and Kubernetes networking along with Docker technology, particularly comparing a service's deployment in swarm versus Kubernetes.

### Topics:
* Kubernetes Networking
	* Kubernetes control plane
	* Deploying a single pod
	* Deploying a single pod through a YAML manifest
	* Deploying a ReplicaSet
	* Deploying a ClusterIP service
	* Kubernetes DNS
	* Deploying a NodePort service
* Docker Swarm
	* Deploying a Service in Docker Swarm

------------------------------