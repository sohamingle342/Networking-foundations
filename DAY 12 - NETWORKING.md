## Day 16: Voice over IP (VoIP) & Real-Time Communication Protocols

### 🧠 Core Concepts Learned (In Simple English)
* **What is VoIP?** Voice over IP converts human analog voice signals into digital data packets and transmits them over standard IP networks instead of traditional PSTN (Public Switched Telephone Network) copper lines.
* **Core VoIP Architecture Components:**
  * **VoIP Server (IP-PBX):** The central controller that acts like a digital switchboard, routing internal/external calls and managing extensions (e.g., Asterisk, FreePBX, Cisco CallManager).
  * **VoIP Clients:** 
    * *Hard Phones:* Dedicated physical desk phones with built-in mini computers.
    * *Soft Phones:* Software applications installed on a PC or smartphone (e.g., Zoom, Microsoft Teams, Zoiper).
  * **VoIP Gateways:** Hardware bridges that connect an internal VoIP network to traditional telephone lines (PSTN).
* **Protocols & Codecs:**
  * **SIP (Session Initiation Protocol):** The universal signaling standard used to establish, maintain, and terminate call connections.
  * **Codecs (e.g., G.711, G.729):** Software algorithms that compress and encode voice data to balance voice quality vs. bandwidth consumption.
* **Latency & Quality of Service (QoS):** Voice traffic is extremely sensitive to delay. Standard phone calls need latency under 150ms. QoS rules prioritize voice packets over regular web traffic on routers to prevent choppy audio or dropped calls.
