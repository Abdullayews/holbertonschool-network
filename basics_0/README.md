<div align="center">

# 🌐 Networking basics #0

**OSI layers, LAN vs WAN, MAC vs IP, TCP vs UDP — the invisible wiring, explained.**

[![Bash](https://img.shields.io/badge/Bash-5.x-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Networking](https://img.shields.io/badge/Networking-TCP%2FIP-005C84?style=flat-square)](#)
[![Holberton](https://img.shields.io/badge/Holberton-Foundations-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this project

Before you configure a network, you have to *speak* network. This project is
concept-first: the OSI model layer by layer, the difference between a LAN,
a WAN and the Internet, what a MAC address is versus an IP address, and why
TCP and UDP exist as opposites — reliability versus speed.

Each question is answered in its own file, and the practical part closes
with a Bash script that answers the only question that matters in the
field: *is this host actually on the network?* (`ping`)

## 🎯 Concepts covered

- The OSI model — 7 layers, who lives where
- LAN, WAN, and the Internet — scale and ownership
- MAC address vs IP address — physical vs logical
- TCP vs UDP — the reliability/speed trade-off
- Well-known ports: SSH (22), HTTP (80), HTTPS (443)
- `ping` and `netstat` — the field diagnosis kit

## 📂 Files

| File | What it does |
|---|---|
| [`0-OSI_model`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_0/0-OSI_model) | Answer: the 7 layers, from physical bits to applications |
| [`1-types_of_network`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_0/1-types_of_network) | Answer: LAN vs WAN vs the Internet |
| [`2-MAC_and_IP_address`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_0/2-MAC_and_IP_address) | Answer: what each address identifies and where it lives |
| [`3-UDP_and_TCP`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_0/3-UDP_and_TCP) | Answer: the two transport protocols, compared |
| [`4-TCP_and_UDP_ports`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_0/4-TCP_and_UDP_ports) | Answer: ports — SSH 22, HTTP 80, HTTPS 443 |
| [`5-is_the_host_on_the_network`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_0/5-is_the_host_on_the_network) | Bash: pings an IPv4 and reports reachability |

## ⚙️ Requirements

- 🐧 Ubuntu 20.04 LTS
- 📝 Answers written in text files, one per question
- 🧹 Bash scripts pass Shellcheck, start with `#!/usr/bin/env bash`

## 🚀 Try it yourself

```bash
./5-is_the_host_on_the_network 8.8.8.8    # ping-based reachability check
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-network](../README.md)**
