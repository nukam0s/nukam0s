## Projects

A deep source-level audit of every repository I own — **31 repositories (5 public, 26 private)** — grouped by visibility and purpose. Names link directly to each repo.

### Public repositories

**IRC scripts & plugins**

- [Pollinations](https://github.com/nukam0s/Pollinations) — Limnoria plugin giving IRC bots Pollinations.ai text and image generation, channel-context replies, model listing and retry fallback.
- [allinone](https://github.com/nukam0s/allinone) — Eggdrop Tcl script adding eight channel protections (flood, repeat, badwords, caps, spam, DNSBL) plus per-channel lists and flag permissions.

**Games & leaderboards**

- [IdleGame-ranking](https://github.com/nukam0s/IdleGame-ranking) — Static GitHub Pages leaderboard for the IdleGame IRC RPG: player table, rarity-economy and network charts, PT/EN toggle.

**Dev tools**

- [zoo-balance](https://github.com/nukam0s/zoo-balance) — VS Code extension showing Zoo Code balance, usage and cache savings in the status bar via an encrypted stored session cookie.

**Profile**

- [nukam0s](https://github.com/nukam0s/nukam0s) — Profile repository for this profile README; contains only a README index of all owned repositories, with no source code.

### Private repositories

**IRC bots**

- [aibot](https://github.com/nukam0s/aibot) — IRC AI bot using OpenAI chat plus embeddings for relevance, per-network JSON memory, admin controls and channel rejoin retry.
- [espnbot](https://github.com/nukam0s/espnbot) — IRC betting bot on ESPN fixtures/live scores with per-user bets, pickle storage and TLS impersonation to bypass Akamai.
- [futcom](https://github.com/nukam0s/futcom) — IRC football commentary and voting bot polling ESPN, with OpenAI natural-language command mapping and league backoff.
- [gulag](https://github.com/nukam0s/gulag) — Undernet #gulag bot: vote-driven voice/op, pattern-based gags with expiry, autovoice and activity tracking.
- [idlegame](https://github.com/nukam0s/idlegame) — Multi-network IRC idle RPG (pydle + aiosqlite) with economy, items, pets, duels, raids, arena, quests and a generated web ranking.
- [jupe](https://github.com/nukam0s/jupe) — IRC nick-reclaim bot that holds a priority nick list and verifies ownership through WHO checks and retries.
- [la](https://github.com/nukam0s/la) — IRC protection bot with DNSBL lookups, kick/ban-rate attack mode, persistent kick history, gags and OpenAI replies.
- [newsbot](https://github.com/nukam0s/newsbot) — Multi-network IRC news bot posting Google News RSS headlines on a timer or on demand, with keyword filters.
- [pybot](https://github.com/nukam0s/pybot) — IRC protection bot with per-channel rules (warn/kick/tempban/ban), badword lists, user flags and multilingual messages.
- [relaybot](https://github.com/nukam0s/relaybot) — IRC relay bot bridging channels across networks with duplicate suppression, flood control, badword filtering and watchdog rejoin.

**Discord bots**

<<<<<<< HEAD
- [carequest](https://github.com/nukam0s/carequest) — Discord RPG economy bot in Portuguese: casino, stock market, shop, missions, achievements, raid bosses and AI-generated questions.
- [plexbot](https://github.com/nukam0s/plexbot) — Discord bot for TMDB lookups, Radarr/Sonarr release alerts and Google Sheets payment tracking.
- [rsem](https://github.com/nukam0s/rsem) — Discord bot for nursing teams: shift schedules, reaction-based swaps, reminders, resident clinical logs and AI shift summaries.
- [seerr-discord-bot](https://github.com/nukam0s/seerr-discord-bot) — Discord slash-command front end for Seerr: search/request films and series, quotas, account linking and admin sync.
- [velho](https://github.com/nukam0s/velho) — Discord AI persona bot on Pollinations/mistral storing user facts and relationships, summarizing channels and replying human-like.

**Apps & web**

- [agenda](https://github.com/nukam0s/agenda) — Offline Android personal diary/expense agenda in Kotlin: Room, Compose, reminders, PIN/biometric lock, CSV/PDF export and widget.
- [carequest_web](https://github.com/nukam0s/carequest_web) — Single-file Flask dashboard over the CareQuest SQLite DB: user XP, portfolio value, market and jackpot statistics.
- [lezirias](https://github.com/nukam0s/lezirias) — Next.js 16 + Prisma/SQLite website and admin CMS for the Residência Sénior Lezírias care home, with news, gallery and contacts.
- [nuke-irc-client](https://github.com/nukam0s/nuke-irc-client) — Windows IRC client in PySide6 with multi-server, ZNC playback, themes, channel monitor, DCC and offline translation.
- [o-Meu-Saldo](https://github.com/nukam0s/o-Meu-Saldo) — Flutter personal-finance app with monthly cycles, category budgets, savings goal, pie charts, profiles and SQLite storage.
- [plataforma-denuncias](https://github.com/nukam0s/plataforma-denuncias) — Express/EJS site for anonymous elder-abuse reports, with hidden admin area, CSRF/rate-limit hardening and sql.js storage.
- [Pollinations-local-private-app](https://github.com/nukam0s/Pollinations-local-private-app) — Single-file browser client for the Pollinations API: chat, image/video generation, gallery, model pricing and balance checks.
- [RSEM-Escala](https://github.com/nukam0s/RSEM-Escala) — Flutter app showing the RSEM nursing shift roster from Google Sheets, with offline cache, shift reminders and quick notes.
- [RSEM-Fisio](https://github.com/nukam0s/RSEM-Fisio) — Offline Flask app for a physiotherapy clinic: appointment calendar, patient records, price list and PDF invoicing.
- [videosatellite](https://github.com/nukam0s/videosatellite) — Framework-free PHP 8/SQLite website and backoffice CMS for a Sesimbra telecom/security installer, incl. solar simulator and quotes.
=======
- [carequest](https://github.com/nukam0s/carequest) — Discord bot for care-home residents ("CareQuest"), with SQLite persistence and a services layer plus config/data folders.
- [plexbot](https://github.com/nukam0s/plexbot) — Discord bot (discord.py) integrating Radarr/Sonarr and Google Sheets via service accounts to track/announce movie and series releases; TMDB enrichment.
- [rsem](https://github.com/nukam0s/rsem) — Discord bot for shift scheduling ("Residência Sénior Egas Moniz"): reads/writes Google Sheets (gspread), handles shift swaps/requests/reminders, OpenAI-assisted, exports to Excel.
- [seerr-discord-bot](https://github.com/nukam0s/seerr-discord-bot) — Bot Discord para Seerr (discord.py): Request movies/tvshows linking Discord ID ↔ Seerr account bilingue.
- [velho](https://github.com/nukam0s/velho) — Small Discord bot prototype/legacy experiment (bot.py); an early, abandoned iteration alongside the AI IRC bots.

**Apps & web**

- [carequest_web](https://github.com/nukam0s/carequest_web) — Flask web companion to CareQuest, serving a SQLite-backed achievements/stats page.
- [nuke-irc-client](https://github.com/nukam0s/nuke-irc-client) — Nuke IRC Client: Windows IRC client in Python/PySide6 supporting multiple servers, ZNC bouncers, IRCv3 server-time, themes, channel monitor and ignore/notify lists & more.
- [o-Meu-Saldo](https://github.com/nukam0s/o-Meu-Saldo) — "O Meu Saldo": Flutter (Android/iOS/Web) personal-finance app with dashboard, monthly cycles, category budgets and a savings pot.
- [plataforma-denuncias](https://github.com/nukam0s/plataforma-denuncias) — "Plataforma Envelhecer com Qualidade": web platform for anonymous reporting of elder abuse/neglect (Node.js 20, Express 4, EJS, SQLite via sql.js, helmet/rate-limit/CSRF) with a hidden admin area.
- [RSEM-Escala](https://github.com/nukam0s/RSEM-Escala) — RSEM Escala: Android Flutter app showing the shift roster for Residência Sénior Egas Moniz, synced from Google Sheets, with personal view, "who's working now", reminders and offline support.
- [RSEM-Fisio](https://github.com/nukam0s/RSEM-Fisio) — "Fisioterapia Egas Moniz": local web app to manage a physiotherapy outpatient clinic (bookings, patients, pricing, treatments, billing/periodic reports); runs on Windows via localhost, offline, portable runtime.
>>>>>>> b64a31ffff3defcf5198ed93626b059f1b966d37

**Tools & scripts**

- [ponto](https://github.com/nukam0s/ponto) — Console script that logs into the DIMEP Kairos timeclock portal and exports all employees' punch records to one Excel sheet.

## Stack / interests

- Python
- Discord bots
- IRC bots/tools
- AI / automation workflows
- Game projects
- Small utility services and scripts

## Note

Repository counts and descriptions come from a deep source-level audit of each project — READMEs, manifests, entry points, database schemas, and route/command definitions — rather than from GitHub metadata alone. All 31 repositories are original work: none is archived and none is a fork.
