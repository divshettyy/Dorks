# 🔍 Dorks

[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen?logo=github)](https://divshettyy.github.io/Dorks/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)](CONTRIBUTING.md)
[![Last Commit](https://img.shields.io/github/last-commit/divshettyy/Dorks)](https://github.com/divshettyy/Dorks/commits/main)
[![Stars](https://img.shields.io/github/stars/divshettyy/Dorks?style=social)](https://github.com/divshettyy/Dorks/stargazers)

**1000+ Google and Shodan dorks for recon, OSINT, and bug bounty hunting.**  
Categorized · Searchable · Copy-to-clipboard · Served live via GitHub Pages.  
Enter your target domain once — every dork updates instantly.

---

## 🌐 Live Pages

| Page | Description |
|------|-------------|
| [**Home**](https://divshettyy.github.io/Dorks/) | Landing page |
| [**Google Dorks**](https://divshettyy.github.io/Dorks/Google.html) | 1000+ Google search operator dorks |
| [**Shodan Dorks**](https://divshettyy.github.io/Dorks/Shodan.html) | 200+ Shodan queries |

---

## 📋 What's inside

| File | Contents |
|------|----------|
| `Google.html` | Dork list pulled live from [TakSec/google-dorks-bug-bounty](https://github.com/TakSec/google-dorks-bug-bounty). Covers exposed docs, login portals, directory listings, config/backup files, cloud leaks, and more. Auto-substitutes your target domain into every query. |
| `Shodan.html` | 200+ curated Shodan queries: exposed databases, webcams, IoT/ICS devices, remote-access panels, cloud storage, SSL misconfigs, and default credentials. Copy-to-clipboard on every card. |

### Google dork categories
- Exposed files & documents
- Login and admin panels
- Directory listings
- Config and backup files
- Database errors
- Cloud bucket leaks
- API keys and tokens
- Company and employee recon

### Shodan dork categories
- Login panels & dashboards
- Exposed databases (MongoDB, Redis, Elasticsearch, MySQL, PostgreSQL…)
- Remote access (RDP, VNC, SSH, Telnet)
- Web servers with default pages
- IoT & industrial (cameras, DVRs, PLCs, MQTT)
- Cloud & storage (Docker APIs, MinIO, Consul)
- SSL/certificate recon
- Sensitive files & configs

---

## 🚀 Usage

1. Open the [live page](https://divshettyy.github.io/Dorks/)
2. Click **Google Dorks** or **Shodan Dorks**
3. Type your target domain in the input box
4. Click any dork to open the search directly — or **Copy** to paste into Burp/CLI
5. For Google dorks: supports multiple domains separated by commas

---

## 🤝 Contributing

Found a dead dork, a better query, or want to add a new category?  
See [CONTRIBUTING.md](CONTRIBUTING.md) for how to submit — PRs are welcome.

---

## ⚠️ Responsible use

These queries are for **authorized security testing, research, and education only**.  
Only probe systems you own or have explicit written permission to test.  
Misuse of these queries may be illegal in your jurisdiction.
