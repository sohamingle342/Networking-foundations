## Day 11: Core Internet Protocols - TCP/IP & Subnet Masking

### 🧠 Core Concepts Learned 
* **The TCP/IP Protocol Suite:** The foundation stack of the internet. 
  * **IP (Internet Protocol):** Operates at Layer 3 to route data packages between separate networks.
  * **TCP (Transmission Control Protocol):** Operates at Layer 4 to guarantee that data arrives reliably, perfectly ordered, and without errors using data windowing.
* **Subnet Masking (The Network Filter):** Every IP address contains two pieces of information: the Network ID and the Host ID. A Subnet Mask acts like a filter that tells the computer exactly where the network identifier ends and the individual device identifier begins. 
* **DHCP Lease Lifecycles:** Dynamic Host Configuration Protocol (DHCP) doesn't give a device an IP address forever; it *leases* it for a specific window of time. By default, a client machine will automatically attempt to renew its lease when the time hits the 50% expiration mark.
* **Default Gateway:** The physical or virtual router that serves as the exit door for a network. If a device tries to send data to an IP address that is not on its local subnet, it instantly forwards the data to the Default Gateway to handle the outside routing.
