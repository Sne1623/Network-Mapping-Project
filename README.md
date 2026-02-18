# Network Mapping & Connectivity Report
**Course:** The Bits and Bytes of Computer Networking  
**Author:** Sinenhlanhla Khumalo  

---
## 1. Introduction
This report documents my home network setup and demonstrates connectivity testing using basic networking commands (`ipconfig` and `ping`).  
The purpose of this report is to:  
- Map the network layout from my device to the internet  
- Identify key network details such as IP address, subnet mask, and default gateway  
- Verify internal and external connectivity  
- Demonstrate understanding of TCP/IP, routing, and DNS

  ---
## 2. Network Layout
The diagram below shows my home network setup, illustrating the connection from my laptop to the router and the internet:

<img width="1408" height="768" alt="DIAGRAM" src="https://github.com/user-attachments/assets/c8833814-1522-459e-b238-8fd20f6a6d48" />


> This diagram represents how my laptop communicates with the router and other devices on the network.

---

## 3. Device Details
- **Host Device:** Windows Laptop  
- **Local IP Address:** 172.20.6.88  
- **Subnet Mask:** 255.255.254.0  
- **Default Gateway (Router IP):** 172.20.6.1  
- **Network Type:** Private Wi-Fi  

> These details were obtained using the `ipconfig` command in Command Prompt.
<img width="755" height="434" alt="IPCONFIGG" src="https://github.com/user-attachments/assets/de95e9f7-89a4-4d68-9cd2-ae1ec125c97f" />

---

## 4. Connectivity Test Results

### Ping to Router (Internal)
Tested connection to my default gateway:

✅ Internal network is stable; the device communicates successfully with the router.
<img width="499" height="301" alt="PING TEST" src="https://github.com/user-attachments/assets/4a4f6583-7c0e-40f7-b958-398d0ba52572" />

---

### Ping to Google (External)
Tested internet connectivity:

✅ External connectivity is stable; DNS resolution and internet access are working properly.
<img width="518" height="270" alt="PING COOGLE" src="https://github.com/user-attachments/assets/db66e172-d887-4f0a-abc4-ba5a35a1ee5d" />

---

## 5. Observations & Conclusion
- The network is fully functional, with **low latency** to the router (1ms) and **stable internet connection** (14–15ms to Google).  
- DNS resolution is successful, confirming that devices on this network can access the internet reliably.  
- Overall, the network is **stable and properly configured**, with all devices communicating as expected.  

---

> This report demonstrates network mapping, internal/external connectivity testing, and understanding of IP addressing, routing, and TCP/IP principles.
