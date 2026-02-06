*This project has been created as part of the 42 curriculum by mjusta.*

## Description

**NetPractice** is a hands-on **networking project** with 10 progressive levels focused on core fundamentals. By troubleshooting and configuring broken network diagrams, you practice **TCP/IP (IPv4) addressing**, **subnet masks/CIDR**, **default gateways**, and basic routing, while reinforcing the idea of **network layers (OSI/TCP-IP)** in a browser-based training environment.

## Instructions

### 1. Launch the training interface

1. Download the file attached on the project page and extract it anywhere you want.
2. In the extracted folder run:

```bash
./run.sh
```

If it doesn't work, start a local server manually:

```bash
python3 -m http.server 49242
```

Then open in your browser (preferably chrome):

```
http://localhost:49242
```

### 2. Solve levels + export your configs
- Enter your 42 login in the interface (important).
- For each level:
  - Modify only the editable (unshaded) fields until objectives are satisfied.
  - Use **Check again** to validate your solution.
  - Use the logs at the bottom if something is wrong (invalid IP, missing gateway, etc.).
  - Click **Get my config** to export your solution **before moving to the next level**.
- Use the Evaluation tab to generate random levels for extra practice or evaluation.

### 3. Submission requirements
- You must submit **10 exported configuration files** (one per level).
- Place all 10 files at the **root of the repository**.

## Concepts studied
- TCP/IP addressing (IPv4)
- Subnet masks, CIDR notation, and subnetting
- Default gateway and basic routing (routing tables)
- Routers vs switches (L2 vs L3 devices)
- OSI model and the TCP/IP model (layering)

## Resources
- [TCP/IP addressing (IPv4 / IP address)](https://en.wikipedia.org/wiki/IP_address)
- [Subnetting + subnet masks + CIDR](https://www.practicalnetworking.net/stand-alone/subnetting-mastery/)
- [Private IPv4 ranges (RFC1918)](https://www.rfc-editor.org/rfc/rfc1918.html)
- [Routers / switching / subnets (vendor-style doc)](https://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13788-3.html?utm_source=chatgpt.com)
- [OSI model (layers)](https://en.wikipedia.org/wiki/OSI_model)
- [Default gateway (concept)](https://en.wikipedia.org/wiki/Default_gateway)

## Study workflow

- I used ChatGPT as a study assistant to clarify networking concepts and to quiz me.
- I rewrote the concepts in my own words and practiced solving random levels without relying on external tools.

## Notes
- **Same subnet**: devices can communicate directly (no router needed).
- **Default gateway**: where a host sends traffic outside its subnet.
- **Router**: connects different networks (L3).
- **Switch**: connects devices in the same LAN (L2).


https://medium.com/@imyzf/netpractice-2d2b39b6cf0a

https://42-cursus.gitbook.io/guide/4-rank-04/netpractice/theory