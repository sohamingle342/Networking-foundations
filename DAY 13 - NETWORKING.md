## Day 19: Centralized Identity & Domain Architecture - Windows Active Directory

### 🧠 Core Concepts Learned 
* **Workgroups vs. Domains:**
  * *Workgroup (Peer-to-Peer):* Every computer manages its own local user accounts and passwords. Managing 50 computers means manually updating permissions on 50 different machines—unscalable for companies.
  * *Domain (Centralized Network):* A centralized database controls all accounts, passwords, and security rules. You log into *one* domain account from *any* computer on the network.
* **Domain Controller (DC):** The central server holding the security database (Active Directory). When a user logs in, the DC authenticates their credentials and issues "access keys" to grant or deny access to network resources.
* **PDC & BDC Structure:**
  * **Primary Domain Controller (PDC):** Holds the master read/write copy of the security database.
  * **Backup Domain Controller (BDC):** Holds a read-only copy of the database for redundancy; if the PDC crashes, a BDC can be promoted to keep network authentication alive.
* **Organizational Units (OUs) & Permissions vs. Security Policies:**
  * *Permissions:* Access granted to shared resources like files, folders, and printers.
  * *Security Policies:* System-level rules (password length, locking desktop settings, disabling USB drives).
* **Trust Relationships:** Secure links created between two different corporate domains that allow users from Domain A to log into machines or access files in Domain B.
