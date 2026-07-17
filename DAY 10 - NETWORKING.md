### 🧠 Core Concepts Learned 
*  Server:A server is simply any computer running software that provides resources, data, or services to other machines (clients) over a network. While you *can* turn a basic laptop into a server, corporate environments use specialized enterprise machines.
* **Enterprise Hardware vs. Desktop Hardware:** Corporate servers are built for 100% continuous uptime. They use distinct hardware components to prevent crashes:
  * **Xeon/EPYC Processors:** Designed to handle massive, non-stop workloads.
  * **Redundant Power Supplies (RPS):** Multiple power inputs so if one power brick burns out, the backup instantly keeps the machine running without downtime.
  * **ECC (Error-Correcting Code) RAM:** Memory that constantly checks itself for data corruption errors on the fly to prevent crashes.
  * **RAID (Redundant Array of Independent Disks):** Grouping multiple hard drives together so if one drive physically breaks, the data survives on the other disks without dropping the server.
* **Common Server Roles in a Business:**
  * **Authentication Servers:** The central brain that validates usernames/passwords and manages access permissions across the network.
  * **File & Print Servers:** Central storage zones for corporate files and network printers.
  * **Web & Database Servers:** The engines hosting web applications and securely cataloging data tables.
