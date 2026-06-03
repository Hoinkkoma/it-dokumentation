# 📚 IT-Dokumentation

**Zentrale Dokumentationssammlung für IT-Infrastruktur, Netzwerk und Serversysteme**

---

## 📋 Beschreibung

Dieses Repository dient als **Wissensbasis für IT-Infrastruktur und Systemintegration**. Es dokumentiert Best Practices, Konzepte und Konfigurationen für Netzwerk- und Server-Administration.

### ✨ Schwerpunkte
- 🌐 **Netzwerk** – IP-Konzepte, Routing, Firewalls, VLAN
- 🖥️ **Server** – Windows & Linux Administrations- und Betrieb
- 🔐 **Sicherheit** – Access Control, Policies
- 📊 **Monitoring** – Überwachung und Logging
- 🔧 **Best Practices** – Standards und Workflows

---

## 📂 Projektstruktur

```
it-dokumentation/
├── README.md
├── CONTRIBUTING.md         # Beitragsleitfaden
├── LICENSE                 # GPL-3.0
├── netzwerk/               # Netzwerkdokumentation
│   ├── ip-konzepte.md
│   ├── routing.md
│   ├── firewall-grundlagen.md
│   ├── vlan.md
│   └── dns-dhcp.md
├── server/                 # Serververwaltung
│   ├── linux-administration.md
│   ├── windows-server.md
│   ├── rollen-dienste.md
│   ├── backup-restore.md
│   └── monitoring.md
├── cloud/                  # Cloud-Infrastruktur
│   ├── kubernetes.md
│   ├── docker.md
│   └── cloud-security.md
└── tools/                  # Hilfsdateien & Tools
    ├── konfiguration-templates/
    └── checklisten/
```

---

## 🌐 Netzwerk-Dokumentation

### IP-Konzepte
- IPv4 Subnetting und CIDR
- IPv6 Grundlagen
- Adressierung und Routing

### Routing & Switching
- Statisches vs. Dynamisches Routing
- VLANs und Trunk-Konfiguration
- Spanning Tree Protocol (STP)

### Firewall & Sicherheit
- Firewall-Regeln
- DMZ-Konzepte
- NAT und PAT

---

## 🖥️ Server-Dokumentation

### Linux Server
- Installation & Konfiguration
- User- und Gruppenmanagement
- Package Management (APT, YUM)
- Systemservices
- Monitoring & Logging

### Windows Server
- Active Directory (AD)
- Gruppenrichtlinien (GPO)
- Server-Rollen
- Backup & Disaster Recovery
- Hyper-V Virtualisierung

---

## 🚀 Verwendung

### Dokumentation hinzufügen

1. **Branch erstellen:**
   ```bash
   git checkout -b feature/neue-dokumentation
   ```

2. **Datei hinzufügen:**
   ```bash
   # Im entsprechenden Verzeichnis
   touch netzwerk/mein-thema.md
   ```

3. **Changes committen:**
   ```bash
   git add .
   git commit -m "docs: Neue Dokumentation zu [Thema]"
   ```

4. **Push & Pull Request:**
   ```bash
   git push origin feature/neue-dokumentation
   ```

---

## 📝 Markdown-Template

```markdown
# Thema-Titel

## Übersicht
Kurzbeschreibung

## Konzepte
Detaillierte Erklärung

## Konfiguration
Schritt-für-Schritt Anleitung

## Best Practices
Empfehlungen

## Häufige Fehler
Troubleshooting

## Siehe auch
Links zu verwandten Themen
```

---

## 🔒 Sichtbarkeit & Sicherheit

⚠️ **Wichtig:** Dieses Repository enthält sensitive Informationen:
- IP-Konzepte und -Pläne
- Serverrollen und Konfiguration
- Security-Policies

🔐 **Aktuell:** Private (falls nicht anders konfiguriert)

**Vor Veröffentlichung prüfen:**
- ❌ Keine echten IP-Adressen
- ❌ Keine Passwörter/Secrets
- ❌ Keine Personendaten
- ✅ Nur generische Beispiele

---

## 🤝 Richtlinien für Beiträge

Bitte siehe [CONTRIBUTING.md](CONTRIBUTING.md) für Details.

**Kurz zusammengefasst:**
- ✅ Klare, verständliche Sprache
- ✅ Mit Beispielen
- ✅ Links zu Quellen
- ✅ Regelmäßig aktualisieren
- ✅ Feedback willkommen

---

## 📚 Git-Cheat Sheet

### Grundlagen
```bash
# Repository klonen
git clone https://github.com/Hoinkkoma/it-dokumentation.git

# Status prüfen
git status

# Changes hinzufügen
git add .

# Commit erstellen
git commit -m "Nachricht"

# Zu Server pushen
git push
```

### Mit Branches arbeiten
```bash
# Neuen Branch erstellen
git checkout -b feature-name

# Zwischen Branches wechseln
git checkout main

# Branch löschen
git branch -d feature-name

# Branches zusammenführen
git merge feature-name
```

### Pull Requests
1. Branch pushen: `git push origin feature-name`
2. In GitHub einen Pull Request erstellen
3. Review durchführen
4. Merge & löschen

---

## 🛠️ Tools & Ressourcen

- 📖 **Linux Man Pages:** https://man7.org/
- 🪟 **Microsoft Docs:** https://docs.microsoft.com/
- 🔍 **RFC Editor:** https://www.rfc-editor.org/
- 🐧 **ArchWiki:** https://wiki.archlinux.org/

---

## 📊 Checklisten

### Serverinitialisierung
- [ ] OS Installation
- [ ] Netzwerk konfigurieren
- [ ] Sicherheit hardening
- [ ] Monitoring setup
- [ ] Backup erstellen

### Netzwerk-Audit
- [ ] IP-Planung
- [ ] Firewall-Regeln
- [ ] VLAN-Struktur
- [ ] Dokumentation
- [ ] Tests

---

## 🐛 Bekannte Probleme

- [ ] Einige Linux-Seiten benötigen Aktualisierung (Ubuntu 24.04)
- [ ] Windows Server 2022 Dokumentation in Arbeit
- [ ] Cloud-Sektion ausgebaut werden

---

## 📄 Lizenz

GNU General Public License v3.0 – Siehe [LICENSE](LICENSE)

---

## 👨‍💻 Autor

[Hoinkkoma](https://github.com/Hoinkkoma) - 2026

**Basierend auf Best Practices und Erfahrungen aus der IT-Infrastruktur**

---

*Zuletzt aktualisiert: Juni 2026*

⭐ **Wenn die Dokumentation hilfreich ist, hinterlasse gerne einen Star!**
