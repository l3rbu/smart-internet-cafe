<img width="1265" height="506" alt="image" src="https://github.com/user-attachments/assets/be2f12aa-f14e-4038-b473-12e0f1f64569" /># Smart Internet Cafe Network Simulation

This is a Cisco Packet Tracer simulation project of a smart internet cafe with integrated IoT devices and VLAN-based segmentation.

The network spans three floors and implements dynamic routing, DHCP, ACL filtering, and internal VoIP communication.

---

## Files

- `FINAL_PROJECT.pkt` — Main simulation file

---

## Topology Overview

- 1st Floor
> <img width="1535" height="572" alt="image" src="https://github.com/user-attachments/assets/ec27b47f-bcc2-4850-8572-9083dc1cc1f7" />

- 2nd Floor
> <img width="1266" height="483" alt="image" src="https://github.com/user-attachments/assets/43ee2f4a-9f27-4c4e-960f-3552e2152f50" />

- 3rd Floor
> <img width="1265" height="506" alt="image" src="https://github.com/user-attachments/assets/79051f07-67b0-46cc-8a8c-672adf8b6c47" />

---

## Features

- 3 routers and 5 switches across 3 floors
- DHCP-enabled IP assignment
- OSPF dynamic routing
- VLAN segmentation across 7 functional zones
- ACL rules for inter-VLAN control
- IoT devices connected via home gateway

---

## VLAN Breakdown

| VLAN ID | Name             | Description                          |
|---------|------------------|--------------------------------------|
| 10      | Server Room      | Internal servers and services        |
| 20      | Admin / Cashier  | Staff operations and billing         |
| 30      | PS4 Gaming Zone  | Console clients (zone 1)             |
| 40      | PS5 Gaming Zone  | Console clients (zone 2)             |
| 50      | PC Gaming Zone   | Desktop gaming users                 |
| 70      | VoIP A           | First group of internal IP Phones    |
| 80      | VoIP B           | Second group of internal IP Phones   |

---

## IoT Devices

- Webcam / CCTV
- Air Conditioner
- Smart LED lighting
- RFID-enabled smart door
- Smoke detector
- Fan
- Coffee machine

All devices are connected through a home gateway and can be controlled or monitored within the network.

---

## How to Run

1. Open `FINAL_PROJECT.pkt` using Cisco Packet Tracer.
2. Use **Realtime** or **Simulation** mode to explore.

---

## Academic Information

This project was developed for academic purposes at:

Universitas Pendidikan Indonesia (UPI)  
Faculty of Mathematics and Natural Sciences  
Department of Computer Science

---

## Author

GitHub: [@l3rbu](https://github.com/l3rbu)
