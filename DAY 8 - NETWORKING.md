## Day 10: Network Diagnostics - Discovery, Mapping, and DOS Commands

### 🧠 Core Concepts Learned 
* **What is Network Mapping?** The process of identifying all the active devices (computers, servers, routers, printers) connected to a local network to visualize its physical and logical structure.
* **Core Mapping Mechanisms:**
  * **ICMP (Internet Control Message Protocol):** Sending "Echo Requests" (pinging a system) to see if a machine is online.
  * **Port Scanning:** Checking which network ports (like Port 80 for HTTP or Port 443 for HTTPS) are open on a target system to figure out what services/applications are running.
  * **SMB (Server Message Block):** Checking for Windows file and printer sharing endpoints to identify shared folder structures.
  * **SNMP (Simple Network Management Protocol):** A specialized protocol using "Agents" installed on devices and "Traps" (triggers/alerts) to automatically report hardware and system health back to a central console.
* **Essential Command Line Tools (DOS):**
  * `ipconfig /all`\: Shows all current network configurations (IP address, Subnet Mask, Default Gateway, and physical MAC address).
  * `ipconfig /release` & `/renew`: Drops the current dynamic IP address and requests a fresh one from the local DHCP server.
  * `ping [target]`: Sends test packets to a target IP or domain to check connection latency and packet loss.
  * `tracert [target]`: Displays the step-by-step path (the routers/hops) that data packets take to reach a destination.
