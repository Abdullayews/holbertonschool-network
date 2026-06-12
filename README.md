<div align="center">

# 🌐 Networking — The Invisible Wires

**From OSI models to Netplan configs to the google.com question.**

*Three projects: the concepts, the commands, and the full journey of a URL.*

[![Bash](https://img.shields.io/badge/Bash-5.x-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Networking](https://img.shields.io/badge/Networking-TCP%2FIP%20%C2%B7%20DNS%20%C2%B7%20OSI-005C84?style=for-the-badge)](#)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-20.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com)
[![Holberton](https://img.shields.io/badge/Holberton-Foundations-E44D26?style=for-the-badge)](https://www.holbertonschool.com)

</div>

---

## 🧭 About this repository

Networking learned in three moves. **Concepts first**: the OSI model,
LAN/WAN, MAC vs IP, TCP vs UDP — every question answered in its own file.
**Commands second**: configuring a machine's IP and netmask with Netplan,
listing interface addresses, and opening a listening port with netcat.
**The grand finale**: the legendary *"what happens when you type
google.com and press Enter?"* — answered as a blog post and an
infrastructure diagram covering DNS, handshakes, firewalls, load balancers
and rendering.

## 📚 The projects

| Project | What it covers |
|---|---|
| [`basics_0/`](basics_0/README.md) | OSI layers, network types, MAC/IP, TCP/UDP, ports — and a ping script |
| [`basics_1/`](basics_1/README.md) | Netplan IP configuration, attached IPs, listening on localhost |
| [`what_happens_when_your_type_google_com_in_your_browser_and_press_enter/`](what_happens_when_your_type_google_com_in_your_browser_and_press_enter/README.md) | The full journey — blog post + diagram |

## 🛠️ Environment

- Ubuntu 20.04 LTS · Bash 5
- Scripts pass **Shellcheck** and start with `#!/usr/bin/env bash`
- Each project folder has its own README with concepts & usage

## 🚀 Try the scripts

```bash
git clone https://github.com/Abdullayews/holbertonschool-network.git
cd holbertonschool-network/basics_0
./5-is_the_host_on_the_network 8.8.8.8      # is it reachable?
cd ../basics_1
./2-port_listening_on_localhost 98 &        # open a listener…
nc localhost 98                             # …and talk to it
```


## 👤 Author

**Muhəmməd Abdullayev** — Computer Engineering student · Qarabağ University & Holberton School

<p>
<a href="https://github.com/Abdullayews"><img src="https://img.shields.io/badge/GitHub-@Abdullayews-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://t.me/arasss08"><img src="https://img.shields.io/badge/Telegram-@arasss08-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
<a href="mailto:08abdullayevv@gmail.com"><img src="https://img.shields.io/badge/Email-08abdullayevv@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

> 🇦🇿 Part of my Holberton School journey — Foundations & Specializations, one repo at a time.

