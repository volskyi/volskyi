### Hi, I'm Oleksii (Alex) Volskyi 👋

Product Owner who ships. I take products from problem to production, then run them: spec, architecture,
deploy, monitoring, and the boring parts that keep them alive.

Most of my work lives in private repositories (client code, live payments, credentials). Each one has
a public **overview repo** below that describes what it does and how it's built.

---

#### 🚀 In production

| Project | What it is | Stack | |
|---|---|---|---|
| **[BookLab](https://github.com/volskyi/booklab-overview)** | Trilingual online bookshop running the full commerce loop: checkout, card payments, shipping integrations, AI shopping assistant | OpenCart 4 · PHP 8.3 · MySQL · Redis · Docker · Caddy · Gemini | [live ↗](https://booklabtienda.es) |
| **[FleetLedger](https://github.com/volskyi/fleetledger-overview)** | Multi-tenant ERP for road-transport companies: trip-level profitability, driver payroll, invoicing, AI assistant | FastAPI · Next.js · PostgreSQL · PWA | [live ↗](https://fl.volskyi.pro) |
| **[ResoNative](https://github.com/volskyi/resonative-overview)** | Deterministic loudspeaker and room design platform. Physics from cited literature, no guesswork | Python · NumPy/SciPy · vanilla JS UI | [live ↗](https://rn.volskyi.pro) |
| **[Sonarq](https://github.com/volskyi/sonarq-overview)** | Bilingual marketing site and content hub for an acoustic design studio | Astro · Tailwind · Cloudflare Pages | [live ↗](https://sonarq.es) |

#### 🤖 Automation, running 24/7

| Project | What it is | Stack |
|---|---|---|
| **[TG bot](https://github.com/volskyi/techno-madrid-overview)** | Runs a music community on its own: anti-spam with new-member quarantine and strikes, plus daily scans for events with Ukrainian artists, drafted for one-tap publishing | Python · Telegram Bot API · GraphQL · SQLite · systemd |
| **[insta-c](https://github.com/volskyi/insta-c-overview)** | Instagram growth assistant for a local bookshop: finds and scores likely readers, enforces a safe daily budget, a human makes every move | Python · FastAPI · Playwright · SQLite |
| **[Resale Scout](https://github.com/volskyi/resale-scout-overview)** `codename` 🕶️ | Finds underpriced second-hand gear on classifieds marketplaces: recognises models from photos, estimates real margin, pushes deals to Telegram | Python · Playwright · LLM vision · SQLite · Telegram |
| **[Task Radar](https://github.com/volskyi/task-radar-overview)** `codename` 🕶️ | Watches an online work platform for newly published paid tasks and alerts within seconds, with self-renewing sessions and hot-standby failover | Python · Playwright · IMAP · systemd · Telegram |
| **[Niche Probe](https://github.com/volskyi/niche-probe-overview)** `codename` 🕶️ | Validation-first affiliate hub: eight niches live at once, every click tracked before any offer exists, money only follows the winners | HTML · vanilla JS · Python generator |

<sub>🕶️ <code>codename</code>: names changed to protect the innocent, and the websites these bots keep an eye on.</sub>

#### 🔌 Hardware + software

| Project | What it is | Stack |
|---|---|---|
| **[Mist Controller](https://github.com/volskyi/mist-controller-overview)** | Humidity-controlled misting, temperature monitoring and scheduled lighting: ESP8266, DHT22 sensor and two relays, with a phone dashboard ([live](https://volskyi.github.io/mist-controller-dashboard/)) | ESP8266 · Arduino · MQTT/TLS · PWA |
| **[Receiver Remote](https://github.com/volskyi/receiver-remote-overview)** | Web remote for a Yamaha RX-V2700 over RS-232C (DE-9, null-modem, 9600 8N1), live sync with the front panel; plus fault-finding on a Denon AVR-3808 over telnet | Python · pyserial · SSE |

#### 🛠️ Tools

| Project | What it is | Stack |
|---|---|---|
| **[Earprint](https://github.com/volskyi/earprint-overview)** | Keeps a large music library in order: duplicates found by sound (fingerprints + sample-level null test), remixes and edits told apart, tags repaired via AcoustID, every move undoable | Python · Chromaprint · NumPy · SQLite |
| **[CryptoRisk Scanner](https://github.com/volskyi/cryptorisk-scanner-overview)** | 0–100 risk score for a crypto wallet in seconds: BTC, ETH, USDT and USDC on Bitcoin, Ethereum, Tron, TON and Solana, OFAC and on-chain sanctions checks, no backend | JavaScript · public explorers/RPC |

#### 🧰 Open source

- **[SwitchFix](https://github.com/volskyi/SwitchFix)**: macOS menu-bar utility that fixes text typed in the wrong keyboard layout

---

#### How I work

- **Verify where it takes effect.** A green deploy isn't proof; the response header, the DB row and the real browser are.
- **Own the infrastructure.** I run my own Hetzner and home-server fleet: Docker, Caddy, systemd timers,
  tested backups, secret scanning on every repository.
- **Write it down.** Every project carries a runbook and a changelog, so the next person (or the next me) starts informed.

🌐 [volskyi.pro](https://volskyi.pro)
