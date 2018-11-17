# Kubernetes
In this repository I do learn Kubernetes. Sections I am going to follow,

> [Kubectl](#Kubectl)  

### Vitrualization technology
* Docker is one implementation of container based vritualization technologies.
* Pre-Virtualization world,
 - Huge cost on purchasing physical machine
 - Configure servers may take time
 - Hard to migrate
* Hypervisor-based Virtualization
 - Hypervisor-providers(VMware, VirtualBox)
 - Now, AWS and MS Azure
 - Cost efficient - no upfront committment
 - Easy to scale
 - Limitations: Kernal resource duplications(all OSs are build on single hypervisor), Application portability issue\
 - Virtualization happens hardware level
 - OSs share kernal resources on base server
* Container Virtualization
 - Instead of a Hypervisor, Virtualization happens in Container Engine
 - Virtualization happens at the operating system level
 - Cost efficient
 - Fast Deployment
 - Guranteed Portability

### Runtime Isolation - A Benifit of Container Virtualization
* Isolating runtime environment
* Running two different applications in two different containers with the different JRE versions.

### Kubectl
* Kubectl provides access to nearly every Kubernetes.
* Primary command line access tool

