# 🎬 Home Automated Media Stack

Een zelfgehost media-systeem ontworpen voor maximale automatisering, privacy en hoge kwaliteit streaming. Dit project is waar mijn passie begon voor het beheren van self-hosted servers.

## 🌟 Belangrijkste Features
- **Volledige Automatisering (The ARR-Stack):** Automatische discovery en verwerking van media via Sonarr, Radarr en Prowlarr.
- **Media Management:** Geautomatiseerde renaming, sortering en metadata van content.
- **Makkelijke Streaming:** High-performance transcoding en streaming naar elk device via Jellyfin.
- **Safe & Secure Downloads:** Geïntegreerde download-clients (qBittorrent) die via een beveiligde VPN-gateway werken.
- **Centralized Dashboard:** Een op maat gemaakt dashboard (eigen website) voor direct overzicht van de server en actieve services.
- **GPU Transcoding:** Intel QuickSync
- **Hardware:** HP Engage Flex Pro | i5 8500 | 24gb ram | 512gb m.2 SSD | 1tb hdd

## 🛠️ Tech Stack
- **Hypervisor:** Proxmox VE (Draait op eigen server)
- **Containers:** Portainer in een LXC.
- **Automated:** Sonarr, Radarr, Prowlarr, Bazarr (ondertiteling).
- **Networking:** Nginx Proxy Manager met SSL-certificaten voor veilige toegang zonder vervelende meldingen.

## 🏗️ De Architectuur
De kracht van deze setup zit in de connectie tussen de verschillende platformen. In plaats van handmatige acties, communiceert de stack onderling:

1. **Request:** Een nieuwe titel wordt aangevraagd.
2. **Search:** Prowlarr indexeert de beste bronnen op basis van kwaliteitsprofielen.
3. **Download:** De download client download de file.
4. **Stream:** De media-server werkt de bibliotheek bij en maakt de content gelijk beschikbaar.

## 🧱 Systeem Overzicht
![Jellyfin](https://img.shields.io/badge/Jellyfin-0081C9?style=for-the-badge&logo=Jellyfin&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57024?style=for-the-badge&logo=Proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white)

## 📸 Preview

---
*Ontwikkeld door Tijn - 2026*
