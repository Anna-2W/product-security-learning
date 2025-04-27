# Local Area Network (LAN) Topologies
---

![ChatGPT Image 27 avr  2025, 19_19_59](https://github.com/user-attachments/assets/5dc49de0-5db1-475b-920c-1db46f9d3e29)


## 📚 What is a Topology?

In networking, **topology** refers to the physical or logical layout of a network — how devices are connected to each other.

---

## ⭐ Star Topology

- Each device connects to a central device (like a switch or hub).
- Data travels through the central device.

✅ Advantages:
- Highly reliable (isolated failures).
- Easy to scale (add more devices).

❌ Disadvantages:
- Expensive (more cables + central hardware).
- Central device failure brings down the whole network.

---

## 🚌 Bus Topology

- All devices share a single backbone cable.
- Data travels along the cable to reach all devices.

✅ Advantages:
- Cheap to set up (few cables, minimal hardware).
- Easy initial deployment.

❌ Disadvantages:
- High risk of bottlenecks (if many devices communicate).
- Difficult troubleshooting.
- Single point of failure (the backbone cable).

---

## 🔵 Ring Topology

- Devices are connected in a closed loop (circle).
- Data travels around the ring until it reaches its destination.

✅ Advantages:
- Easier troubleshooting (single path for data).
- Less prone to heavy traffic bottlenecks.

❌ Disadvantages:
- If one device or cable fails, the entire network can break.
- Slower data delivery (data may pass through multiple devices).

---

# 📡 Switches

- A **switch** connects multiple devices within the same network.
- It knows where each device is (which port) and sends data directly to the correct one.
- Much more efficient than old hubs.

✅ Example switch sizes: 4, 8, 16, 24, 32, 64 ports.

---

# 🌐 Routers

- A **router** connects different networks together.
- It performs **routing**, meaning it decides the best path for data to travel across networks.

✅ Adds redundancy: multiple paths = higher reliability if one path fails.

---

# 🎯 Quick Summary

| Concept | Key Point |
|:---|:---|
| Star Topology | Central device controls traffic; scalable but expensive. |
| Bus Topology | Cheap but risky (single cable). |
| Ring Topology | Loop connection; one failure can break the network. |
| Switch | Smart device inside a network. |
| Router | Connects different networks and routes data.

---
