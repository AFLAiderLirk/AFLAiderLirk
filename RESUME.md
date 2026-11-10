# Dmitry Rudakov
## Cybersecurity / Linux / Network Security Intern · Junior C++ Developer

**Contact:** [dima2006.ruda@gmail.com](mailto:dima2006.ruda@gmail.com) · [GitHub](https://github.com/AFLAiderLirk)  
**Target:** remote internship or entry-level role in information security, infrastructure / network security, or C++ development.

## Profile

Information Security student at **Novgorod State University** and cybersecurity student at **School 21**. I have hands-on educational experience with Linux services, network protocols, PCAP investigations, threat detection, firewall policies, and VPN configuration. I write small security-related tools in Python and work on personal C++ and Java projects.

**Several completed School 21 cybersecurity projects have been accepted** (author-confirmed). The original submissions and assessed repositories are **private on GitLab**; my GitHub presents **independent descriptions of work and skills**, not school source material or solutions.

## Technical skills

- **Programming:** C++, Java; Python and Bash for educational scripts, analysis, and automation.
- **Linux / systems:** Kali Linux, users and permissions, processes and services, SSH, cron, Apache, nginx, Postfix, Logwatch, basic iptables.
- **Networking:** OSI/TCP/IP, IPv4, TCP/UDP, ARP, ICMP, DNS, DHCP, NAT, VLAN, OSPF, HSRP; GNS3 and Cisco IOS labs.
- **Traffic analysis:** Wireshark, tshark, tcpdump, Scapy, PCAP investigation, TLS handshake and DNS-tunneling indicators.
- **Threat detection:** YARA, Suricata, MITRE ATT&CK, IDS/IPS fundamentals, version-based exposure research (FOFA/CVE), PyMongo and mitmproxy.
- **Secure networks:** pfSense, IPsec/IKEv2 site-to-site VPN, OpenVPN, HTTPS/TLS, PKI, Easy-RSA and certificates, firewall policies and time-based access rules.
- **Other tools:** Git/GitLab/GitHub, VirtualBox, Maven, Webots, Minecraft Paper API.

## School 21 · practical cybersecurity projects

[**Public portfolio summary**](https://github.com/AFLAiderLirk/networking-lab-notes) — original assessed artifacts remain in private GitLab repositories.

### Infrastructure and secure network design

- Designed segmented small-business LAN and DMZ lab architecture, asset inventories, access controls and layered security measures.
- Deployed **two pfSense CE 2.6.0 VMs** with separate LAN subnets and an isolated WAN connection.
- Configured **IPsec/IKEv2 site-to-site VPN** and verified established IKE SA and installed Child SA.
- Prepared firewall rules restricting RDP (TCP 3389), SSH (TCP 22), and scheduled SMTP (TCP 25) access; documented equivalent iptables rules.

### Attack investigation and security configuration checks

- Mapped simulated incidents to **MITRE ATT&CK** tactics and techniques.
- Built a **Python/PyMongo** lab scanner checking for MongoDB database enumeration without authentication on authorized networks; positive detection on an intentionally exposed database was not separately validated.
- Built and locally tested a **mitmproxy** addon that records HTTP form-submission metadata without storing form values or credentials.
- Analyzed PCAP data indicating DNS tunneling and reconstructed session evidence; used FOFA/CVE references for non-intrusive exposure research.

### Detection engineering and behavioral analysis

- Developed **three YARA** rules using text and hexadecimal indicators, with file-size matching, and checked all nine combinations across three supplied samples.
- Created **four Suricata** detection signatures for suspicious TCP/C2-like, HTTP, ICMP, and DNS patterns; validated alerts against a provided PCAP.
- Implemented a **Python/pynput/statistics** educational program comparing inter-keystroke intervals between repeated manual text entries.

### Secure communications and networking labs

- Configured nginx **HTTPS/TLS** and investigated handshake captures.
- Practiced **OpenVPN**, Easy-RSA, CA/certificates and TUN interface troubleshooting.
- Worked with isolated **CryptoPro NGate / CSP / GOST TLS** scenarios.
- Used **GNS3/Cisco IOS** for routing, switching, VLAN and protocol simulation.

These are educational exercises and **do not imply production experience**. School 21 acceptance applies to the completed assessed project areas reported above; no acceptance is claimed for every separate training scenario.

## Personal development projects

**[Webots Mower](https://github.com/AFLAiderLirk/webots-mower) · C++**  
Prototype robotic lawn-mower controller with GPS/IMU, sensor-driven obstacle avoidance, navigation state machine and coverage grid. End-to-end coverage accuracy is not yet validated.

**[AiderKits](https://github.com/AFLAiderLirk/aiderkits) · Java / Minecraft Paper**  
Configurable kits, inventory menus, permissions and cooldowns. Maven build verified; further in-server validation pending.

**[AFLQuestBoard](https://github.com/AFLAiderLirk/AFLQuestBoard) · Java / Minecraft Paper**  
Quest objectives and rewards, player progress persistence and inventory GUI.

**[Cryptography learning notes](https://github.com/AFLAiderLirk/cryptography-learning-notes)**  
Educational notes on hashing, XOR, symmetric encryption, RSA, Diffie–Hellman and PKI.

Additional personal C++ projects exist but are not currently published.

## Education and languages

- **Novgorod State University** — Information Security student.
- **School 21** — practical cybersecurity training.
- **English:** B2 (self-reported), technical documentation.

## Experience scope and publication policy

Personal projects and controlled educational labs only. No commercial cybersecurity employment, production deployments or independently verifiable certifications are claimed. Private coursework, original tasks, graded code, captures, challenge flags, credentials, certificates and VPN secrets are not published.
