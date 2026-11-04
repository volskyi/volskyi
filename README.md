### Hi, I'm Oleksii (Alex) Volskyi 👋

Product Owner who ships. I take products from problem to production, then run them: spec, architecture,
deploy, monitoring, and the boring parts that keep them alive.

Most of my work lives in private repositories (client code, live payments, credentials). Each one has
a public **overview repo** below that describes what it does and how it's built.

---

#### 🚀 In production

| Project | What it is | Stack | |
|---|---|---|---|
| **[BookLab](https://github.com/volskyi/booklab-overview)** | Trilingual online bookshop with real orders, card payments, shipping integrations and an AI shopping assistant | OpenCart 4 · PHP 8.3 · MySQL · Redis · Docker · Caddy · Gemini | [live ↗](https://booklabtienda.es) |
| **[FleetLedger](https://github.com/volskyi/fleetledger-overview)** | Multi-tenant ERP for road-transport companies: trip-level profitability, driver payroll, invoicing, AI assistant | FastAPI · Next.js · PostgreSQL · PWA | private |
| **[ResoNative](https://github.com/volskyi/resonative-overview)** | Deterministic loudspeaker and room design platform. Physics from cited literature, no guesswork | Python · NumPy/SciPy · vanilla JS UI | [live ↗](https://rn.volskyi.pro) |
| **[Sonarq](https://github.com/volskyi/sonarq-overview)** | Bilingual marketing site and content hub for an acoustic design studio | Astro · Tailwind · Cloudflare Pages | [live ↗](https://sonarq.es) |

#### 🤖 Automation, running 24/7

| Project | What it is | Stack |
|---|---|---|
| **[Resale Scout](https://github.com/volskyi/resale-scout-overview)** | Finds underpriced second-hand gear on classifieds marketplaces: recognises models from photos, estimates real margin, pushes deals to Telegram | Python · Playwright · LLM vision · SQLite · Telegram |
| **[Task Radar](https://github.com/volskyi/task-radar-overview)** | Watches an online work platform for newly published paid tasks and alerts within seconds, with self-renewing sessions and hot-standby failover | Python · Playwright · IMAP · systemd · Telegram |

#### 🧰 Open source

- **[SwitchFix](https://github.com/volskyi/SwitchFix)**: macOS menu-bar utility that fixes text typed in the wrong keyboard layout

---

#### How I work

- **Verify where it takes effect.** A green deploy isn't proof; the response header, the DB row and the real browser are.
- **Own the infrastructure.** I run my own Hetzner and home-server fleet: Docker, Caddy, systemd timers,
  tested backups, secret scanning on every repository.
- **Write it down.** Every project carries a runbook and a changelog, so the next person (or the next me) starts informed.

🌐 [volskyi.pro](https://volskyi.pro)
