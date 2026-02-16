# Lab: Logical and Physical Mode Exploration

## 📝 Objective
The primary goal of this lab is to explore the Cisco Packet Tracer interface, navigate the **Physical Wiring Closet**, and establish physical/logical connectivity between end devices and networking hardware.

## 🕸️ Topology
![Network Topology](topology.png)
> *Note: Ensure the topology image is in the same directory as this README file.*

## ⚙️ Configuration Steps
The following steps were performed to initialize the device and set a unique identity for the router.

### 1. Accessing the CLI
Connected to the console and entered the privileged mode.

### 2. Setting the Hostname
Used the following commands to rename the router for easier identification:

```ios
Router> enable
Router# configure terminal
Enter configuration commands, one per line. End with CNTL/Z.

Router(config)# hostname Edge_Router_Backup
Edge_Router_Backup(config)# end
Edge_Router_Backup#