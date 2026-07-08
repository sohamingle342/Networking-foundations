# Networking-foundations
## Day X: Layer 1 - Network Cabling & Physical Infrastructure

### 🧠 Core Concepts Learned
* **Twisted Pair Cable Shielding:** The tight twists in Ethernet wire pairs aren't random—they act as built-in shielding to cancel out electromagnetic interference (EMI).
* **Cat5e vs. Cat6:** Cat5e is the standard 1 Gbps workhorse. Cat6 handles up to 10 Gbps for short runs but costs more. 
* **Plenum Cabling:** Special fire-safe cable used inside ventilation and HVAC ducts. It costs 5x more because it doesn't release deadly, toxic gas when burning.
* **Structural Constraints:** Copper runs have a strict **100-meter (330-foot)** limit. Any longer, and the signal degrades into useless data.
* **Home Run Topology:** Cables must run unbroken from the wall jack straight to the **Patch Panel** in the server room. Splicing or patching lines in the middle creates major failure points.

### 🛠️ Hands-On Skills Mastered
* **T568B Termination:** Learned how to strip, straighten, and align the 8-wire matrix into the standard US layout: `White-Orange ➔ Orange ➔ White-Green ➔ Blue ➔ White-Blue ➔ Green ➔ White-Brown ➔ Brown`.
* **Crimping & Punchdowns:** Mastered using crimpers for RJ45 connectors and an impact punchdown tool (with a 110 blade) to cleanly terminate wires into patch panels.
* **Hardware Diagnostics:** Tested lines using a Continuity Tester to catch wire breaks, and a **Toner/Wand probe** to trace unlabeled wires through a building using audio frequencies.

### 🏢 Cloud Security Alignment
Cloud data centers (like AWS or Azure) are built on massive networks of physical copper and fiber-optic lines. True **Zero-Trust Security** starts at Layer 1. Understanding cable limitations, home-run architecture, and secure patch panels helps you identify physical vulnerabilities, prevent hardware-level network bottlenecking, and ensure maximum data center uptime.
