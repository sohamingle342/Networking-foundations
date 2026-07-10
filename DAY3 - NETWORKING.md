## Day 4: Theoretical Architecture - The 7-Layer OSI Model

### 🧠 Core Concepts Learned 
The OSI (Open Systems Interconnection) model is a 7layer reference framework used to standardize how data travels across a network.

* **Layer 7 - Application Layer:** The interface the user interacts with directly (e.g., Google Chrome web browser using HTTP/HTTPS, or email clients using SMTP).
* **Layer 6 - Presentation Layer:** Handled primarily by the Operating System. It formats, encrypts, decompresses, and translates data so the application layer can read it (e.g., converting text into ASCII or SSL/TLS encryption mapping).
* **Layer 5 - Session Layer:** Manages, establishes, and terminates the continuous communication sessions between two distinct network endpoints.
* **Layer 4 - Transport Layer:** Controls the delivery of data. Handles flow control, packet segment windowing, and reliability checks using **TCP** (connection-oriented) or **UDP** (connectionless) protocols.
* **Layer 3 - Network Layer:** Handles logical routing across separate networks. This is where **IP Addresses** and routers function to find paths for data packets.
* **Layer 2 - Data Link Layer:** Responsible for local node-to-node data transfer on the same network. This is where hardware **MAC Addresses**, Address Resolution Protocol (ARP), and switches operate.
* **Layer 1 - Physical Layer:** The actual hardware layer where data is converted into raw binary electrical, radio, or light pulses traveling over cables or Wi-Fi.
