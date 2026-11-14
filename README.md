<div align="center">

# 🏠 Homelab

**My self-hosted setup at home: storage, apps, networking and monitoring, all run on my own hardware.**

![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![TrueNAS](https://img.shields.io/badge/TrueNAS-0095D5?style=flat-square&logo=truenas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![UniFi](https://img.shields.io/badge/UniFi-0559C9?style=flat-square&logo=ubiquiti&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

</div>

---

## What is a homelab?

A homelab is a small server setup at home, a bit like running your own private cloud. Instead of paying for online storage and apps, I host them myself, which is also a great way to learn how real infrastructure works.

## 🧱 How it's put together

| Layer | What runs it | What it does |
|---|---|---|
| 🖥️ **Virtualization** | Proxmox | Splits one physical server into several virtual machines and containers |
| 💾 **Storage** | TrueNAS | Private file storage, shared to every device over SMB |
| 🐳 **Apps** | Docker, managed with Arcane & Portainer | Runs each self-hosted app in its own container |
| 📡 **Network** | UniFi | Wi-Fi, switching and firewall for the whole house |

## 🧰 Services

| | Service | In plain English |
|:-:|---|---|
| 💾 | **TrueNAS** | My own private storage, shared across every device in the house |
| 🐳 | **Arcane & Portainer** | A dashboard for starting, stopping and managing all my apps |
| 📡 | **UniFi** | Runs the home network: Wi-Fi, switches and firewall |
| 📝 | **Trilium** | A personal wiki for notes, guides and ideas |
| 🔄 | **Watchtower** | Keeps every app automatically up to date |
| 📊 | **Beszel & Grafana** | Live graphs of how everything's running, with alerts if something breaks |

## 🌱 What's next

- ☁️ Bringing **Microsoft Azure** into the mix for off-site and hybrid setups
- 🐧 Getting deeper into **Linux virtualization**
- 🌐 Levelling up the **network** side

---

<div align="center">
<sub>Part of <a href="https://github.com/uxmbra">@uxmbra</a>'s projects · <i>grinding servers by day, aim trainers by night</i></sub>
</div>
