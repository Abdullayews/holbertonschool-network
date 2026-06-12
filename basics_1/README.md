<div align="center">

# 🛠️ Networking basics #1

**Configuring IPs, reading interfaces, and listening on localhost — hands on.**

[![Bash](https://img.shields.io/badge/Bash-5.x-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Networking](https://img.shields.io/badge/Networking-TCP%2FIP-005C84?style=flat-square)](#)
[![Holberton](https://img.shields.io/badge/Holberton-Foundations-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this project

Concepts become commands. This project configures a machine's **IP and
netmask** (the Netplan way, on an Ubuntu server), lists the addresses
attached to all its interfaces, and — the gateway drug to networking —
opens a **listening port on localhost** with `netcat`, then talks to it
from another terminal.

Three small scripts; three moments where "the network" stops being
abstract.

## 🎯 Concepts covered

- Netplan: configuring a static IP + netmask on Ubuntu 20.04
- `hostname -I` and interface address discovery
- localhost / `127.0.0.1` — why your own machine is a network
- `nc` (netcat): listening on a TCP port
- TCP vs UDP sockets in practice

## 📂 Files

| File | What it does |
|---|---|
| [`0-change_your_home_IP`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_1/0-change_your_home_IP) | Bash: writes a Netplan config with the given IP & netmask |
| [`1-show_attached_IPs`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_1/1-show_attached_IPs) | Bash: prints all IPv4 addresses on all interfaces |
| [`2-port_listening_on_localhost`](https://github.com/Abdullayews/holbertonschool-network/tree/main/basics_1/2-port_listening_on_localhost) | Bash: `nc` listening on a given port of localhost |

## ⚙️ Requirements

- 🐧 Ubuntu 20.04 LTS
- 🧹 Shellcheck-clean Bash, `#!/usr/bin/env bash` shebang

## 🚀 Try it yourself

```bash
./0-change_your_home_IP 192.168.1.2 255.255.255.0   # Netplan update
./1-show_attached_IPs                                # every interface's IPs
./2-port_listening_on_localhost 98                   # nc listening on :98
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-network](../README.md)**
