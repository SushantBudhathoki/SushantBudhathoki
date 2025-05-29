# 👨‍💻 Sushant Budhathoki's Networking Portfolio

📍 Mississauga, Ontario | 📧 sushantbudhathoki@gmail.com | [LinkedIn](https://www.linkedin.com/in/sushant-budhathoki-230037268/)

---

## 🎯 Objective

Aspiring Network Engineer actively preparing for the **Cisco Certified Network Associate (CCNA)** certification. I bring a strong foundation in Computer Science and hands-on experience in networking support roles. This repository documents my learning journey, projects, and skills developed toward becoming a professional network engineer.

---

## 🧠 Skills

- Network Troubleshooting (Layer 1–3)
- TCP/IP, DHCP, DNS, NAT Configuration
- VLANs and Inter-VLAN Routing
- Cisco Packet Tracer & Wireshark
- Hardware Setup & Cable Management
- FTTH (Fiber to the Home) Familiarity
- Network Documentation & Support Ticketing
- Customer-Centric Technical Support

---

## 🧪 Labs and Projects

### 📂 `labs/`
Simulated labs built in Cisco Packet Tracer or GNS3.

- `01-basic-network-topology.pkt`: Simple LAN with static IPs
- `02-vlan-routing.pkt`: VLAN and Inter-VLAN Routing with a Layer 3 switch
- `03-ospf-lab.pkt`: Multi-area OSPF configuration
- `04-nat-configuration.pkt`: Dynamic and Static NAT with internet simulation
- `05-ftth-demo.pkt`: FTTH architecture simulation

Each lab includes:
- `.pkt` file
- `README.md` with objective, topology diagram, configuration steps, and outputs

---

### 📂 `notes/`
My study notes and summaries for CCNA topics:
- `network-fundamentals.md`
- `routing-and-switching.md`
- `ip-services.md`
- `security-fundamentals.md`

---

### 📂 `scripts/`
Basic configuration scripts (CLI) for Cisco devices:
```bash
hostname Router1
enable secret cisco123
interface g0/0
 ip address 192.168.1.1 255.255.255.0
 no shutdown
