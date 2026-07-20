## Day 4: Network Switches & Traffic Management

### 🧠 Core Concepts Learned 

* **Switches vs. Hubs:** 
  * **Hubs (Layer 1):** Blindly repeat incoming signals out to all ports, leading to packet collisions and heavy traffic congestion (Broadcast Storms).
  * **Switches (Layer 2):** Use an internal MAC Address Table to inspect frame headers and deliver data *only* to the specific recipient port, eliminating collisions.
*
*
*   **Duplexing & Performance:**
  * **Half Duplex:** Devices can only talk or listen one at a time (like a walkie-talkie).
  * **Full Duplex:** Devices can send and receive data simultaneously, maximizing speed.
  * **Backplane Speed:** The absolute maximum data throughput a switch's internal architecture can handle simultaneously across all ports.


* **Enterprise Features:**
  * **Managed Switches:** Allow engineers to log in, monitor traffic, map ports, and configure advanced network rules (unlike plug-and-play Unmanaged switches).
  * **VLANs (Virtual Local Area Networks):** Logically segmenting a single physical switch into multiple isolated networks (e.g., separating the Accounting team's computers from the public Guest Wi-Fi).
  * **QoS (Quality of Service):** Prioritizing real-time, time-sensitive data packets (like VoIP phone calls or video streams) over basic file downloads to prevent lag.
  * **Spanning Tree Protocol (STP):** A critical Layer 2 protocol that detects and blocks redundant physical loops between switches to prevent data loops from freezing the entire network.
