# 📚 Virtualization
 
> **Date:** 2026-11-26

> **Category:** Networking 

---

## 🎯 Objective

To understand the concept of virtualization, how virtual machines are created and managed, the role of hypervisors, and how virtualization is used in IT infrastructure and cybersecurity environments.

---

## 📖 Overview

Virtualization is a technology that allows us to create multiple virtual computers or environments on a single physical computer.

Instead of purchasing separate physical computers for different operating systems, virtualization allows us to run multiple virtual machines (VMs) on one physical machine.

Virtualization is commonly used in data centers, cloud computing, software testing, and cybersecurity labs.

---

## 🧠 Key Concepts

### 1.Virtual Machine (VM)

A Virtual Machine is a software-based computer that runs on a physical machine.

##### Examples

- Windows Virtual Machine.
- Ubuntu Virtual Machine.

### 2. Hypervisor

A hypervisor is software that creates, runs, and manages virtual machines by sharing the physical computer's hardware resources.

There are two main types of hypervisors
##### Type 1 – Bare-Metal Hypervisor
- Runs directly on physical hardware.
- Commonly used in enterprise environments and data centers.

##### Type 2 – Hosted Hypervisor
- Runs on top of an existing operating system.
- Commonly used for learning, testing, and personal labs.

---

## 🔍 Example

**Creating a cybersecurity lab**

Suppose we have a Windows 11 laptop and want to practice cybersecurity.

Instead of installing multiple operating systems directly on the laptop, we can use Oracle VirtualBox to create virtual machines.

**For example**
1. Install Oracle VirtualBox on Windows 11.
2. Create an Ubuntu virtual machine.
3. Create a Kali Linux virtual machine.
4. Allocate RAM, CPU, and storage to each VM.
5. Configure network settings.
6. Run both virtual machines independently.
This allows us to practice Linux commands, network monitoring, vulnerability testing, and cybersecurity activities without needing multiple physical computers.

---

## 🧪 Hands-On Practice

Creating and managing a virtual machine using VMware and installing Ubuntu as the guest operating system.

**Tools/Commands Used:**
- VMware Workstation.
- Ubuntu ISO file.

**Steps Performed:**
1. Installed VMware Workstation on the host machine.
2. Downloaded the Ubuntu ISO image from the official Ubuntu website.
3. Created a new virtual machine using VMware.
4. Configured the virtual machine by allocating RAM, CPU, and virtual hard disk space.
5. Selected the Ubuntu ISO file as the installation media.
6. Installed Ubuntu inside the virtual machine.
7. Started the virtual machine and explored the Ubuntu operating system.

**What I Observed:**

- VMware allows multiple virtual machines to run on a single physical computer.
- Ubuntu runs independently as a guest operating system inside the virtual machine.
- CPU, RAM, and storage resources are allocated from the host machine to the virtual machine.
- The virtual machine provides an isolated environment for learning and testing.

---

## 🛡️ SOC / Security Relevance

Virtualization is important in cybersecurity because it provides isolated environments for security testing, malware analysis, incident investigation, and security training.

**SOC / Security use cases:**
- Malware Analysis: Analyze suspicious files inside isolated virtual machines.
- Security Testing: Practice vulnerability assessment in controlled environments.
- SOC Lab Setup: Create virtual machines to simulate real-world enterprise networks.
- Incident Investigation: Examine suspicious activities in a controlled environment.
- Network Monitoring: Practice monitoring network traffic between virtual machines.
- Disaster Recovery: Use VM snapshots and backups to restore systems to previous states.

 Virtual machines provide isolation, but they are not completely risk-free. Malware or attacks can potentially escape a VM through hypervisor vulnerabilities or misconfigurations. Therefore, proper isolation and security controls are important.

---

## 📝 Key Takeaways

- Virtualization allows multiple virtual computers to run on a single physical machine.
- A Virtual Machine has its own operating system and allocated hardware resources.
- A hypervisor is responsible for creating and managing virtual machines.
- Type 1 hypervisors run directly on hardware, while Type 2 hypervisors run on a host operating system.

---

## 📚 Resources
- [TryHackMe](https://tryhackme.com/)
- [Cisco Networking Academy](https://www.netacad.com/)


