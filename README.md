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

```

## 📋 Prérequis

Python 3.8+
Nmap
Gobuster / FFUF
Nikto
Hydra
WhatWeb
🖥️ Utilisation
Lancez l'outil et suivez le menu interactif :
```bash
sudo python3 PentestFramework.py
```
## Modes disponibles :
Option	Description
0	Mode Auto - Scan complet automatique
1-2	Reconnaissance passive & active
3-4	Scanning Nmap & services spécifiques
5-7	Tests web & API
8-10	Injections (SQL, XSS, LFI/RFI)
11-15	Exploitation & post-exploitation
16	Shell interactif avancé

## 📂 Structure des résultats

```bash
reports/
├── scans/          # Résultats Nmap, Nikto, etc.
├── exploits/       # Shells et payloads générés
├── loot/           # Données exfiltrées
└── FINAL_REPORT.txt
```
## 🛡️ Aperçu des fonctionnalités

Scanning exhaustif
- Scan TCP complet de tous les ports
- Scan UDP des ports communs
- Détection OS et versions de services
- Scripts NSE de vulnérabilités
Web & API
- Fuzzing de répertoires (Gobuster/FFUF)
- Détection des technologies (WhatWeb)
- Tests IDOR sur endpoints API
- Scan avec Nikto
Exploitation
- Générateur de reverse shells (Bash, Python, PHP, PowerShell, etc.)
- Webshells multi-formats (PHP, ASP, JSP)
- Commandes de post-exploitation et privesc
Brute Force
- Hydra intégré pour SSH, FTP, HTTP, IMAP, etc.
- Wordlist management automatique

## ⚠️ Disclaimer
Usage éducatif et autorisé uniquement.

Cet outil est destiné aux professionnels de la sécurité et aux étudiants. N'utilisez cet outil que sur des systèmes pour lesquels vous disposez d'une autorisation explicite. L'auteur décline toute responsabilité quant à une utilisation illégale ou non éthique.

📜 Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

<p align="center"> <i>Développé avec Python pour la communauté cybersecurity</i> </p> ```
