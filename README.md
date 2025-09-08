## 🌐 Topologies with Cisco Packet Tracer  

To support **network-level fault communication and monitoring**, we designed multiple topologies in **Cisco Packet Tracer**. These `.pkt` files demonstrate how alerts from the ESP32 or control centers can be propagated in different network setups.  

### 📂 Available Topology Files  

- 🚌 **BUS Topology (`bus_topology.pkt`)**  
  - All devices are connected to a single backbone cable.  
  - Simple and cost-effective but less reliable (failure in backbone disrupts the entire system).  

- 🔀 **Hybrid Topology (`hybrid_topology.pkt`)**  
  - Combination of star, bus, and ring structures.  
  - Provides flexibility, scalability, and better fault tolerance.  

- 🌐 **Mesh Topology (`mesh_topology.pkt`)**  
  - Every device is connected to every other device.  
  - High reliability and redundancy, but expensive in terms of cabling and setup.  

- 🔄 **Ring Topology (`ring_topology.pkt`)**  
  - Devices are connected in a closed loop.  
  - Data travels in one direction, making it efficient but vulnerable if a single link fails.  

- ⭐ **Star Topology (`star_topology.pkt`)**  
  - All devices connect to a central switch/router.  
  - Easy to manage and expand but dependent on the central hub.  

---

### 📊 Usage  

1. Open the desired `.pkt` file in **Cisco Packet Tracer**.  
2. Observe how fault alerts/messages are transmitted across the network.  
3. Compare **latency, reliability, and scalability** between topologies.  
4. Use insights to choose the most suitable topology for **real-world smart grid communication**.  

---

### 📝 Note  
In this project, we implemented **2-phase simulation** for hardware.  
For **3-phase implementations**, refer to our PPT for correct connections and integrate with the above topologies as needed.  
