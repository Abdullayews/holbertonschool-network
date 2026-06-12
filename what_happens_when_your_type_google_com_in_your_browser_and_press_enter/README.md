<div align="center">

# 🔍 What happens when you type google.com and press Enter?

**The full journey: DNS → TCP → firewall → HTTPS → load balancer → server → render.**

[![Bash](https://img.shields.io/badge/Bash-5.x-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Networking](https://img.shields.io/badge/Networking-TCP%2FIP-005C84?style=flat-square)](#)
[![Holberton](https://img.shields.io/badge/Holberton-Foundations-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this project

The legendary interview question, answered as a Holberton project. This
folder contains a full **blog post** and an **infrastructure diagram**
tracing a URL from keystroke to pixels: the browser cache and OS resolver,
the DNS root/TLD/authoritative chain, the ARP and TCP handshake, firewall
traversal, the TLS negotiation, the load balancer picking a server, the
application querying its database — and finally HTML, CSS and JS coming
back to be rendered.

## 🎯 Concepts covered

- DNS resolution — recursive & iterative lookups
- TCP/IP & the 3-way handshake
- Firewalls and encryption (HTTPS/TLS) in the path
- Load balancers and web/application/database tiers
- Browser rendering — parse, paint, execute

## 📂 Files

| File | What it does |
|---|---|
| [`0-blog_post`](https://github.com/Abdullayews/holbertonschool-network/tree/main/what_happens_when_your_type_google_com_in_your_browser_and_press_enter/0-blog_post) | The blog post — every step from Enter key to rendered page |
| [`1-what_happen_when_diagram`](https://github.com/Abdullayews/holbertonschool-network/tree/main/what_happens_when_your_type_google_com_in_your_browser_and_press_enter/1-what_happen_when_diagram) | The diagram — the same flow, drawn |

## ⚙️ Requirements

- 📝 A blog post (`0-blog_post`) + a diagram (`1-what_happen_when_diagram`)
- 🖼️ The `.png` diagrams render the two stacks visually

## 🚀 Try it yourself

```bash
cat 0-blog_post    # the whole story, in order
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-network](../README.md)**
