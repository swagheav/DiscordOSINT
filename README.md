<h3 align="center">VOID//DISCORD — Discord OSINT Directory (Made in 2026)</h3>

<p align="center">
  Public lookup directory for Discord investigations.<br>
  Single HTML file · 30+ tools · No install · No tracking
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VOID-DISCORD-red?style=for-the-badge&logo=discord&logoColor=white" alt="VoidDiscord"/>
  <img src="https://img.shields.io/badge/HTML-Single%20File-orange?style=for-the-badge&logo=html5" alt="HTML"/>
  <img src="https://img.shields.io/badge/Tools-30%2B-blue?style=for-the-badge" alt="Tools"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/badge/Made%20in-2026-purple?style=for-the-badge" alt="2026"/>
</p>

<p align="center">
  <b>Developer:</b> 𝐕𝐎𝐈𝐃〆𝐇𝐄𝐀𝐕𝐄𝐍 ·
  <a href="https://t.me/he6ca">DM</a> ·
  <a href="https://t.me/SWGHEV">Channel</a>
</p>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [What's Inside](#-whats-inside)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Usage](#-usage)
- [Tool Categories](#-tool-categories)
- [Project Structure](#-project-structure)
- [Legal Disclaimer](#%EF%B8%8F-legal-disclaimer)
- [Contact](#-contact)

---

## 🔍 Overview

**VOID//DISCORD** is a **public OSINT directory for Discord investigations**, delivered as a single HTML file. It's a curated collection of **30+ third-party lookup tools** organized by what they do — ID resolution, username search, server discovery, avatar OSINT, breach checks, and more.

Every entry is a **link-out** to a public website. Nothing in this page:
- authenticates on your behalf
- scrapes Discord or any third-party site
- sends tokens, requests, or telemetry anywhere
- stores any data you enter

You open it, click a tool, it opens the tool's site in a new tab. That's it.

---

## 🧰 What's Inside

| # | Category | Tools |
|---|----------|-------|
| 1 | 🆔 **ID Resolvers** | Cort.Cat · DiscordResolver99 · SeekNow · Discord.ID · DiscordLookup · Discord.Name · Snowflake Lookup |
| 2 | 👤 **Username Search** | WhatsMyName · Sherlock · Namechk · Instant Username · Blackbird |
| 3 | 🏠 **Server Discovery** | Disboard · Top.gg · Discord.me · Discord Server List · DiscordHub · Discadia · DiscordServers.info |
| 4 | 🔗 **Invite Tools** | Invite resolver · Invite lookup · Disboard invite search |
| 5 | 🖼️ **Avatar OSINT** | Discord.ID avatar · CDN · TinEye · Yandex · Google Lens · PimEyes |
| 6 | 🚨 **Breach Check** | HIBP · LeakCheck · DeHashed · IntelX · GhostProject · Snusbase |
| 7 | ⏪ **Archive** | Wayback Machine · Widget Archive · Archive.today · CachedView |
| 8 | 🔑 **API (Passive)** | Developer Portal · API Docs · Discord Status |
| 9 | 🧰 **Community Toolkits** | OSINT Framework · Bellingcat · IntelTechniques · Awesome OSINT · Awesome Discord |

**30+ tools · 9 categories · 1 HTML file**

---

## 📋 Requirements

| Component | Minimum |
|-----------|---------|
| OS | Windows / Linux / macOS / Android / iOS |
| Browser | Any modern browser (Chrome, Firefox, Edge, Safari) |
| Internet | Required (for outbound tool links) |
| Install | **None** — it's one HTML file |

---

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/swagheav/DiscordOSINT.git
cd DiscordOSINT

# That's it — open the file
```

**Open it:**

```bash
# Linux
xdg-open discord-osint.html

# macOS
open discord-osint.html

# Windows
start discord-osint.html
```

**Or in Termux:**
```bash
pkg install python -y
python -m http.server 8080
# then open http://127.0.0.1:8080/discord-osint.html
```

---

## 📖 Usage

1. Open `discord-osint.html` in any browser
2. Browse categories (first 3 expand by default)
3. Type in the **search bar** to filter across all tools
4. Click any tool → opens its public site in a new tab

**Quick examples:**
- **ID lookup** → open **Cort.Cat** → paste a Discord ID
- **Username search** → open **WhatsMyName** → enter handle
- **Server discovery** → open **Disboard** → search keyword/tag
- **Avatar OSINT** → open **TinEye** or **Yandex** → upload avatar image
- **Breach check** → open **HIBP** → enter account email

---

## 🗂️ Tool Categories

### 🆔 ID Resolvers
Resolve a Discord **snowflake ID** to public profile data — account creation date, badges, avatar, banner, mutual servers (where public).

**Tools:** Cort.Cat · DiscordResolver99 · SeekNow · Discord.ID · DiscordLookup · Discord.Name

### 👤 Username Search
Find where a **handle/username** appears across platforms — often reveals Discord-linked accounts.

**Tools:** WhatsMyName · Sherlock · Namechk · Instant Username · Blackbird

### 🏠 Server Discovery
Search **publicly indexed** Discord servers by name, tag, language, or size.

**Tools:** Disboard · Top.gg · Discord.me · Discord Server List · DiscordHub · Discadia · DiscordServers.info

### 🔗 Invite Tools
Resolve or search **public, non-expired** invite codes.

**Tools:** Invite resolver · Invite lookup · Disboard invite search

### 🖼️ Avatar OSINT
Extract and reverse-search avatars and banners from public profiles.

**Tools:** Discord.ID avatar · CDN · TinEye · Yandex · Google Lens · PimEyes

### 🚨 Breach Check
Check if an email linked to a Discord account appears in known breaches.

**Tools:** HIBP · LeakCheck · DeHashed · IntelX · GhostProject · Snusbase

### ⏪ Archive
Find historical versions of public Discord landing pages, widgets, and invite pages.

**Tools:** Wayback Machine · Widget Archive · Archive.today · CachedView

### 🔑 API (Passive)
Official Discord developer resources — for building your own compliant tooling.

**Tools:** Developer Portal · API Docs · Discord Status

### 🧰 Community Toolkits
Curated directories of OSINT tools — broader investigation resources.

**Tools:** OSINT Framework · Bellingcat · IntelTechniques · Awesome OSINT · Awesome Discord

---

## 📂 Project Structure

```
DiscordOSINT/
├── discord-osint.html   # The entire tool
├── README.md
└── LICENSE
```

---

## ⚠️ Legal Disclaimer

> **VOID//DISCORD is designed strictly for authorized OSINT research and educational purposes only.**
>
> - Only investigate accounts/servers you own or have **explicit written permission** to research.
> - Unauthorized use (surveillance, doxxing, harassment, stalking) is **illegal** under GDPR, CCPA, and similar laws worldwide.
> - This page does **not** scrape, authenticate, bypass, or access non-public data. Every entry is a **public website you open manually**.
> - Some tools listed are **paid or freemium** services — verify pricing and terms before using.
> - **The developer assumes no responsibility for misuse. You are solely accountable for your actions.**

---

## 📞 Contact

| Type | Link |
|------|------|
| 📢 **Channel** | [t.me/SWGHEV](https://t.me/SWGHEV) |
| 💬 **DM** | [t.me/he6ca](https://t.me/he6ca) |
| 🐙 **GitHub** | [@swagheav](https://github.com/swagheav) |
| 📦 **Repo** | [github.com/swagheav/DiscordOSINT](https://github.com/swagheav/DiscordOSINT) |

---

<p align="center">© 2026 VOID//DISCORD • All Rights Reserved</p>
