## Day 16: Traffic Management - Bandwidth Throttling & Network Rate Limiting

### 🧠 Core Concepts 
* **What is Bandwidth Throttling?** The intentional control and limiting of upload/download speeds for specific applications or devices on a network to prevent a single process from monopolizing the entire pipe.
* **Why Bidirectional Bandwidth Matters:** Network communication is a two-way street. Even when heavily downloading a massive file, your computer still needs upload bandwidth to send TCP acknowledgment packets (ACKs) back to the server. If your upload speed is completely maxed out, your download speed will drop to a crawl.
* **Local Application Throttling (NetBalancer):**
  * Allows administrators to monitor active network connections per process (PID, local/remote IP, port numbers).
  * Enables rule-based bandwidth limits (e.g., capping a background backup task to 1 Mbps) so web browsing, VoIP calls, and critical terminal sessions remain responsive.
* **Traffic Prioritization:** Classifying network traffic into priority queues (High, Normal, Low, Blocked) to ensure real-time applications receive guaranteed network resources over background file transfers.


### 🧠 Core Concepts Learned 
* **What is SNMP?** Simple Network Management Protocol is an application-layer protocol used by network admins to monitor, collect telemetry, and manage hardware devices across an IP network.
* **Core Components of SNMP:**
  * **SNMP Manager (NMS):** The central monitoring server (e.g., PRTG, SolarWinds, Nagios) that requests data from network devices and displays health dashboards.
  * **SNMP Agent:** Software built into managed devices (routers, switches, firewalls, Linux servers) that gathers local metrics (CPU usage, temperature, bandwidth, uptime) and sends them back to the Manager.
  * **MIB (Management Information Base):** A structured hierarchical text database file stored on the device that defines what data points can be queried.
  * **OID (Object Identifier):** Unique numeric addresses within the MIB that point to specific metrics (e.g., `1.3.6.1.2.1.1.3` for system uptime).
* **SNMP Commands & Operations:**
  * **GET / GET-NEXT:** The Manager asks an Agent for a specific metric.
  * **SET:** The Manager changes a configuration setting on a remote device.
  * **TRAP:** An unprompted notification sent by the Agent to the Manager when an emergency occurs (e.g., a fan fails or a port goes down).
* **Protocol Versions & Security:**
  * **SNMPv1 & SNMPv2c:** Weak security. They use cleartext passwords called **Community Strings** ("public" for read-only, "private" for read-write). Easy for hackers to sniff on the network.
  * **SNMPv3:** Secure enterprise version. Adds user authentication and strong packet encryption (DES/AES) to keep telemetry data private.
