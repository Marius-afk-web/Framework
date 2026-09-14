# 🔒 Pentest Framework

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Linux-orange?style=flat-square)

Framework d'automatisation de tests d'intrusion développé en Python. Outil complet pour la reconnaissance, le scanning, l'exploitation web et la génération de rapports.

## ⚡ Fonctionnalités

- 🔍 **Reconnaissance** : WHOIS, DNS enum, découverte d'hôtes
- 🌐 **Scanning** : Nmap exhaustif (TCP/UDP), détection OS, scripts NSE
- 🕸️ **Web** : Nikto, Gobuster, WhatWeb, FFUF, détection technologies
- 🔌 **API** : Tests IDOR, enumeration endpoints (REST, GraphQL)
- 💉 **Injections** : SQLi avancé, XSS, LFI/RFI
- 🔓 **Exploitation** : 15+ reverse shells, webshells PHP/ASP/JSP
- 🔨 **Brute Force** : Hydra multi-protocoles (SSH, FTP, HTTP, etc.)
- 📊 **Reporting** : Rapports TXT/JSON automatiques structurés

## 🚀 Installation

```bash
# Cloner le repository
git clone https://github.com/Marius-afk-web/Framework/PentestFramework.git
cd pentest-framework

# Lancer l'outil (nécessite sudo pour certains scans)
sudo python3 pentest.py

📋 Prérequis
Python 3.8+
Nmap
Gobuster / FFUF
Nikto
Hydra
WhatWeb
🖥️ Utilisation
Lancez l'outil et suivez le menu interactif :
