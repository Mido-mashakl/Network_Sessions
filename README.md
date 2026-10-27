# Computer Networks – Lecture Notes 🍵

Egyptian Arabic lecture notes for a Computer Networks course, packed into **one self-contained HTML page**. Switch between sessions with the tabs at the top, jump between sections with the sticky nav bar, search a glossary of abbreviations, and read it on desktop or mobile.

> شرح مادة الشبكات بالعامية المصرية في صفحة واحدة، مرتب وسهل المذاكرة منه.

## Contents

| Part | Topics |
|---|---|
| **Session 1** | Network basics, Unicast / Broadcast / Multicast, Hub, Switch, Router, collision & broadcast domains, LAN vs WAN, OSI model (Layers 7 → 2) |
| **Session 2** | Ethernet, Data Link layer, MAC addresses, Physical layer & cables (UTP/STP, Straight-Through, Crossover), TCP 3-way & 4-way handshake, ports & sockets, ARQ |
| **Session 3** | IP addressing, classes A / B / C / D / E, default subnet masks, subnetting with worked example and homework |
| **Session 4** | Access Control Lists (ACL), wildcard masks, Standard & Extended ACLs, Named & Numbered ACLs, router configuration examples |
| **Session 5** | Spanning Tree Protocol (Root Switch, BID, port roles), NAT (private vs public IPs), Static NAT, Dynamic NAT, PAT |
| **Self Study** | Wireshark: what a packet analyzer is, how it works (capture, dissect, filter), the three panes, coloring rules, and reading a real capture |
| **Abbreviations** | A searchable glossary of 63 abbreviations used across all the parts (NAT, LAN, TCP, ACL, ...) with their full forms and the sessions where each appears |

## Usage

1. Download `Network_Sessions.html` (or rename it to `index.html`).
2. Open it in any modern browser (Chrome, Safari, Firefox, Edge).

No build step, no dependencies. Images are embedded inside the file, so it works offline.

> The Cairo font is loaded from Google Fonts. Without internet the page falls back to a system font and everything else still works.

### Host it with GitHub Pages

1. Rename the file to `index.html` and push it to the repo.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select your branch and `/ (root)`.
4. Your notes will be live at `https://<username>.github.io/<repo>/`.

## Features

- Dark blue theme, responsive layout, RTL Arabic text
- Tabs for Sessions 1–5 and Self Study, with a sticky per-part section nav and reading progress bar
- Abbreviations page with live search, grouped by topic, and links back to the sessions
- Code-style blocks for router commands, tables, and embedded diagrams and screenshots

## Author

**AhmedTea 🍵** – [LinkedIn](https://www.linkedin.com/in/ahmed-mostafa-1a8a55300)
