# Task 4 – Setup and Use a Firewall on Windows

## 📌 Objective
Configure and test basic firewall rules to allow or block traffic using **Windows Defender Firewall**.

---

##  What is a Firewall?
A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predefined security rules. It acts as a barrier between a trusted network and an untrusted network (such as the internet).

---

## 🛠 Steps Performed

### 1. Checked Current Firewall Rules
- Opened **Windows Defender Firewall with Advanced Security**.
- Viewed **Inbound Rules** and **Outbound Rules** to see existing configurations.

### 2. Created Rule to Block Telnet (Port 23)
- In **Inbound Rules** → **New Rule** → **Port** → **TCP** → **23**.
- Selected **Block the connection** for all profiles.
- Named the rule **Block Telnet Port 23**.

### 3. Tested the Block
- Enabled Telnet client and used:
  ```cmd
  telnet localhost 23
