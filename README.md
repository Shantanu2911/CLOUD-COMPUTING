# CLOUD-COMPUTING

# 🖥️ Virtualization – Key Concepts & Keywords

## 📌 Introduction
**Virtualization** is a technology that allows multiple operating systems and applications to run on a single physical machine by abstracting hardware resources. It improves **resource utilization, scalability, flexibility, and cost efficiency**, and is a core concept behind **cloud computing**.

---

## 🔑 Core Virtualization Keywords

### 1. Virtualization
The process of creating a **virtual version** of computing resources such as servers, storage devices, networks, or operating systems instead of using physical hardware directly.

---

### 2. Virtual Machine (VM)
A **software-based computer** that runs an operating system and applications just like a physical machine, but shares the host system’s hardware resources.

---

### 3. Host Machine
The **physical system** that provides hardware resources (CPU, RAM, storage) to virtual machines.

---

### 4. Guest Operating System
The operating system that runs **inside a virtual machine**, such as Linux or Windows.

---

### 5. Hypervisor
A software or firmware layer that **creates, manages, and runs virtual machines**.

#### Types of Hypervisors:
- **Type 1 (Bare-metal)**: Runs directly on hardware  
  *Example:* VMware ESXi, Microsoft Hyper-V
- **Type 2 (Hosted)**: Runs on top of a host OS  
  *Example:* VirtualBox, VMware Workstation

---

### 6. Hardware Virtualization
Uses CPU features (Intel VT-x, AMD-V) to allow multiple operating systems to run efficiently on the same hardware.

---

### 7. Full Virtualization
The hypervisor **completely emulates hardware**, allowing unmodified guest operating systems to run.

---

### 8. Para-Virtualization
The guest operating system is **aware of virtualization** and communicates directly with the hypervisor for improved performance.

---

### 9. OS-Level Virtualization (Containerization)
Virtualization at the **operating system level**, where containers share the same OS kernel.

- Lightweight
- Faster than traditional VMs

*Example:* Docker, LXC

---

### 10. Containers
Lightweight, isolated environments that package applications along with their dependencies while sharing the host operating system kernel.

---

### 11. Virtual CPU (vCPU)
A **logical CPU** assigned to a virtual machine and mapped to the physical CPU cores.

---

### 12. Snapshot
A saved **state of a virtual machine** at a specific point in time, useful for backup, testing, and recovery.

---

### 13. Live Migration
The process of **moving a running virtual machine** from one physical host to another **without downtime**.

---

### 14. Resource Pooling
Combining multiple physical resources into a **shared pool** that can be dynamically allocated to virtual machines.

---

### 15. Virtual Networking
The creation of **virtual switches, routers, and network adapters** to connect virtual machines securely.

---

### 16. Virtual Storage
Abstracted storage resources presented to virtual machines as virtual disks, independent of physical storage hardware.

---

### 17. Emulation
A technique where hardware is **fully simulated in software**, allowing execution of programs designed for different architectures (generally slower than virtualization).

---

### 18. Cloud Computing
Virtualization is the **foundation of cloud computing**, enabling:
- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

---

## ⚙️ Benefits of Virtualization
- Improved hardware utilization
- Reduced infrastructure cost
- High scalability
- Faster deployment
- Better disaster recovery
- Improved isolation and security

---

## ⚠️ Challenges of Virtualization
- Performance overhead
- Complex management
- Security risks
- Hardware compatibility issues

---

## 📚 Popular Virtualization Tools
- VMware
- VirtualBox
- Hyper-V
- KVM
- Docker

---

## 🎯 Conclusion
Virtualization is a **fundamental technology** in modern computing that enables efficient resource management, cloud infrastructure, and scalable application deployment. Understanding these keywords is essential for students, developers, and IT professionals.
