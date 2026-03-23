# roundabout

> RoundAbout — Sovereign VPN coordination. BlackRoad fork of Headscale. Self-hosted WireGuard control plane.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# RoundAbout — BlackRoad Road Fleet

> **Sovereign VPN coordination.** Fork of [Headscale](https://github.com/juanfont/headscale).

---

**RoundAbout** is BlackRoad's sovereign fork of Headscale — self-hosted WireGuard coordination replacing Tailscale's control plane. Manage the mesh from your own hardware.

## What's Different

- **Fleet mesh management** — coordinate WireGuard across all 7 nodes
- **No Tailscale dependency** — fully self-hosted control plane
- **ACL policies** — BlackRoad fleet access rules
- **Node discovery** — automatic peer configuration

## Fleet Mesh

| Node | WireGuard IP | Role |
|------|-------------|------|
| Gematria | 10.0.0.1 | Hub |
| Anastasia | 10.0.0.2 | Hub |
| Alice | 10.0.0.3 | Pi |
| Cecilia | 10.0.0.4 | Pi |
| Octavia | 10.0.0.5 | Pi |
| Aria | 10.0.0.6 | Pi |
| Lucidia | 10.0.0.7 | Pi |

## Upstream

Forked from [juanfont/headscale](https://github.com/juanfont/headscale) (BSD 3-Clause upstream).
All BlackRoad modifications are proprietary.

---

**BlackRoad OS, Inc.** — Pave Tomorrow.

*Proprietary. All rights reserved.*
