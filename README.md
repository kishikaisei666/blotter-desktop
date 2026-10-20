<p align="center">
  <img src="docs/img/desk.png" alt="Blotter — Desk overview" width="860">
</p>

<h1 align="center">Blotter</h1>

<p align="center">
  <b>A private, offline trading journal for Windows.</b><br>
  Log every ticket, review every session, and measure your edge — without an account, a subscription, or a cloud.
</p>

<p align="center">
  <a href="https://github.com/kishikaisei666/blotter-desktop/releases/latest"><b>⬇ Download the latest release</b></a>
  &nbsp;·&nbsp;
  <a href="#verify-your-download">Verify your download</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/kishikaisei666/blotter-desktop/releases">Changelog</a>
</p>

---

## Contents

- [Screenshots](#screenshots)
- [Features](#features)
- [Privacy & offline by design](#privacy--offline-by-design)
- [Install](#install)
- [Why Windows warns you (and what to do)](#why-windows-warns-you-and-what-to-do)
- [Verify your download](#verify-your-download)
- [Updating](#updating)
- [Your data & backups](#your-data--backups)
- [FAQ](#faq)
- [Disclaimer](#disclaimer)
- [License](#license)
- [Changelog](#changelog)

---

## Screenshots

| | |
|---|---|
| ![Desk — KPIs, equity curve, daily P&L, open session](docs/img/desk.png) | ![Log trade — symbol filtered by market, Gross / Fees / Net, exchange fee profile with maker / taker](docs/img/log-trade.png) |
| **Desk** — net P&L, win rate, profit factor, expectancy, drawdown, equity curve and daily P&L for the open session's account. | **Log trade** — one drawer for the whole ticket. Gross, fees and net update live; crypto fees come from your exchange profile (maker / taker for entry and exit). |
| ![Session — open session, morning prep, close-out and day log](docs/img/session.png) | ![Ideas — every trade idea with status filters, carry history and bulk actions](docs/img/ideas.png) |
| **Session** — open a trading day by date, prep before the open, close out after the last trade, and browse the day log. | **Ideas** — every trade idea across sessions: filter, search, edit, carry into today, archive or delete. |
| ![Trade review — numbers, timing, plan and after-trade notes](docs/img/trade-review.png) | ![Analytics — equity, drawdown, win-rate gauge, consistency](docs/img/analytics.png) |
| **Trade review** — a read-only summary of one ticket, with previous / next and Edit. | **Analytics** — equity and drawdown, win rate vs break-even, consistency, P&L calendar, playbook performance and more. |
| ![Copy trade to account — same risk % or same size](docs/img/copy-to-account.png) | ![Settings — exchange fee profiles for Binance and Bybit](docs/img/fee-profiles.png) |
| **Copy to account** — one-time copy of a ticket to your other accounts, sized by the same risk % or the same size. | **Exchange fee profiles** — Binance USDⓈ-M and Bybit presets, editable, plus your own exchanges. |

<p align="center"><img src="docs/img/desk-light.png" alt="Blotter — light theme" width="640"><br><i>Light theme. All screenshots use fake demo data.</i></p>

---|---|
| ![Desk — KPIs, equity curve, daily P&L, 14-week heatmap, risk rules](docs/img/desk.png) | ![Log trade — symbol search, Long/Short, levels, confluence, playbook, risk & session tiles](docs/img/log-trade.png) |
| **Desk** — net P&L, win rate, profit factor, expectancy, drawdown, equity curve, daily P&L and a 14-week heatmap. | **Log trade** — one drawer for the whole ticket: entry, stop, target, size calculator, chart screenshots, confluence and playbook. |
| ![Session — morning prep, close-out and day log](docs/img/session.png) | ![Analytics — P&L calendar, playbook performance, R-distribution, hour × weekday](docs/img/analytics.png) |
| **Session** — morning prep before the open, close-out after the last trade, and a searchable day log. | **Analytics** — P&L calendar, performance by setup, R-multiple distribution, hour × weekday heatmap and more. |

*Screenshots use the built-in demo account.*

---

## Features

**Sessions — your trading day, by date**
- **Manual, date-based sessions per account.** You open the session you are trading (today, or any other date) and close it when you are done. Each account has its own open session, and new trades go into it.
- **Morning prep** — mood, news, bias, goals and trade ideas before the open.
- **Close-out** — grade your plan, execution, risk and emotional control, and mark each idea Taken, Skipped, Missed or Carry.
- **Day log** — every trading day with P&L, trades, grade and mood; searchable by notes and symbols.
- **Trading-day start** — group trades by a custom day boundary (e.g. 17:00 New York for futures/FX).

**Trade ideas**
- Plan ideas with symbol, direction, setup, levels and notes, then **Log trade from an idea** to prefill the ticket.
- **Carry over:** ideas still open from earlier sessions are suggested in the next Morning prep — carry them in, or **Dismiss** the ones that are no longer relevant.
- **Ideas manager** — every idea for the account in one place: filter by Open / Carried / Taken / Skipped / Missed / Archived, date range and symbol, search, edit inline, change status, carry into the open session, archive or delete — one at a time or in bulk. Each idea shows its origin day and carry history.

**Journal**
- **Log trade drawer** — Long/Short, entry / stop / target / exit, open and close time in your time zone, chart screenshots (Plan / In trade / After), confluence, playbook and the Risk, Session, Idea, Execution, After and *Also log to* tiles.
- **Symbol search filtered by market** — pick Crypto, Futures, Forex… and the list shows only that market's instruments (with a fallback to other markets if nothing matches).
- **Built-in instruments** across futures, forex, crypto (including Binance TradFi perps **SPYUSDT** and **QQQUSDT**), stocks, options and CFDs with contract multipliers and tick sizes; edit or add your own.
- **Gross / Fees / Net** shown live in the drawer header and in every trade review.
- **Exchange fee profiles** — Binance USDⓈ-M (0.02% maker / 0.05% taker) and Bybit (0.02% / 0.055%) presets, editable, plus your own. Choose maker or taker separately for entry and exit: *fee = entry notional × entry rate + exit notional × exit rate*. Futures keep per-contract fees; saved trades keep their stored fees.
- **Position-size calculator** from your risk per trade (% of current equity) and stop distance.
- **Chip editing** for tags, mistakes and goals — type, press Enter, remove with one click.
- **Trade review** — a read-only summary of any ticket with previous / next navigation and one-click Edit.
- **Copy trade to account** — copy a ticket to other accounts, sized by the same risk % or the same size, using each account's fees and open session. Copies are independent afterwards.
- **Draft autosave** — an unsaved ticket is restored when you reopen Log trade.

**Review**
- **Desk** — KPIs, equity curve, daily P&L, recent trades and a "today" strip with your loss limits and open session.
- **Analytics** — equity and drawdown, win rate vs break-even (with a minimum-sample notice), consistency, streaks, P&L calendar, playbook performance, R-multiple distribution, hour × weekday, emotions vs results, mistakes, MAE / MFE.
- **Blotter** — full trade table with filters, search, review and copy.
- **Risk rules** — daily loss limit in R and %, risk per trade; warnings before you break them.

**Money & data**
- **Multiple accounts** with their own starting balance and currency.
- **Live FX** — daily ECB reference rates convert P&L, fees and risk into your account currency; manual overrides are kept, and offline the last saved rates are used.
- **Full backup** to a single `.zip` (trades, screenshots, settings) and restore; **CSV** export/import with a documented column map; **automatic backups** on every close (last 10 kept).
- **Day and night themes** (or follow Windows), collapsible sidebar, keyboard-friendly.
- **Automatic updates** for the installer version (see [Updating](#updating)).

---

## Privacy & offline by design

Blotter is a local app. **There is no account, no sign-in, no analytics, no telemetry and no ads.** Your trades, notes and screenshots never leave your computer unless you export them yourself.

Blotter makes **exactly two kinds of network requests**, both read-only and both without any of your data:

| Purpose | Host | When | What is sent |
|---|---|---|---|
| Update check | `github.com` / `objects.githubusercontent.com` (this repository's Releases) | On start (if enabled) and when you click *Check for updates* (*Settings → About and updates*) | A standard HTTPS request for `latest.yml`; if a newer version exists, the installer version downloads the new Setup file |
| FX rates (ECB reference rates) | `api.frankfurter.dev` | Once per day on start (*Settings → FX rates → Auto-update daily*, can be turned off) and when you click *Update rates* | The list of currency codes, e.g. `?from=USD&to=EUR,GBP,JPY…` |

That's it. Offline? Blotter works fully offline and keeps the last saved FX rates.

**Hardening.** The app window runs sandboxed with context isolation and no Node.js access; a strict Content-Security-Policy only allows the FX host above; navigation away from the app and new windows are blocked (links open in your browser). Updates are verified against the SHA-512 in `latest.yml` before they run.

> If you paste an `https://` link to a chart image (for example a TradingView snapshot), the image is loaded from that site when you view the trade — just like opening the link in a browser.

---

## Install

Download from **[Releases → Latest](https://github.com/kishikaisei666/blotter-desktop/releases/latest)**. Windows 10 / 11, 64-bit.

| | **Installer** — `Blotter-Setup-<version>.exe` | **Portable** — `Blotter-<version>-portable.exe` |
|---|---|---|
| Admin rights | Not needed (installs for the current user) | Not needed |
| Start menu / desktop shortcut | Yes | No — run the `.exe` directly |
| Automatic updates | **Yes** | No — the app tells you when a new version is out |
| Data location | `%APPDATA%\Blotter\data` | `data\` next to the `.exe` |
| Best for | Most users | USB stick, trying it out, no-install machines |

**Recommended:** the installer. You can move your data between the two at any time with *Settings → Data & backup → Export all (.zip) / Import from .zip*.

---

## Why Windows warns you (and what to do)

Blotter is built by one independent developer and is **not code-signed** yet. A code-signing certificate costs hundreds of dollars a year, and new signed apps still have to build "reputation" before warnings go away. Windows can't tell who published an unsigned app, so it asks you to decide. That is what the warnings mean — not that something bad was found.

**Before you click through, [verify your download](#verify-your-download).** If the hash matches, the file is exactly the one published here.

### Microsoft Defender SmartScreen — "Windows protected your PC"
1. Click **More info**.
2. Check that the file name is `Blotter-Setup-<version>.exe` (Publisher: *Unknown publisher*).
3. Click **Run anyway**.

### Smart App Control (Windows 11)
If Smart App Control is **On**, Windows blocks unsigned apps outright and there is **no "Run anyway" button** and no per-app exception. Your options:
- Keep Smart App Control on and don't use Blotter for now — that's a perfectly reasonable choice; or
- Temporarily turn it off: *Windows Security → App & browser control → Smart App Control settings → Off*, install and run Blotter, then decide whether to turn it back on.

> On Windows 11 builds before the April 2026 update (KB5083769), Smart App Control **cannot be turned back on without resetting Windows** once turned off. Check that you are up to date before changing it, and only do it if you trust the file.

### Antivirus false positives
A few antivirus engines flag unsigned installers built with common tools (Electron + NSIS) using generic names such as *Wacatac*, *Malgent* or "ML/heuristic". You can look up any release on VirusTotal by its SHA-256 (see [Verify your download](#verify-your-download)) to see the full results yourself. If your antivirus quarantines Blotter, verify the hash, restore the file and add an exception — and please [open an issue](https://github.com/kishikaisei666/blotter-desktop/issues) with the engine name so it can be reported as a false positive.

**Never** download Blotter from anywhere other than this repository's Releases page. There are no mirrors, no paid versions and no "cracked" builds.

---

## Verify your download

Every release lists the SHA-256 hash of each file. If your hash matches, the file is byte-for-byte what was published here.

### Hashes

Each release page lists the hashes for that version in this format:

| File | SHA-256 |
|---|---|
| `Blotter-Setup-X.Y.Z.exe` | `<SHA256_SETUP>` |
| `Blotter-X.Y.Z-portable.exe` | `<SHA256_PORTABLE>` |

**Current release — [v0.3.4](https://github.com/kishikaisei666/blotter-desktop/releases/tag/v0.3.4):**

| File | SHA-256 |
|---|---|
| `Blotter-Setup-0.3.4.exe` | `6db940e0a8f28559a83e6e611620b689d4fa14102cc0225066de9abcc0ee0b34` |
| `Blotter-0.3.4-portable.exe` | `3b637bac780f23693a6734fdaa01c274f8f058d60309cc223b1e9795e088cd38` |

For newer versions, always use the hashes on that version's release page.

### Check on Windows (PowerShell)

```powershell
cd $HOME\Downloads
Get-FileHash .\Blotter-Setup-X.Y.Z.exe -Algorithm SHA256
```

Compare the `Hash` value with the table above (case doesn't matter). One-liner that answers True/False:

```powershell
(Get-FileHash .\Blotter-Setup-X.Y.Z.exe).Hash -eq '<SHA256_SETUP>'
```

Command Prompt alternative: `certutil -hashfile Blotter-Setup-X.Y.Z.exe SHA256`

### VirusTotal

- Installer: `https://www.virustotal.com/gui/file/<SHA256_SETUP>`
- Portable: `https://www.virustotal.com/gui/file/<SHA256_PORTABLE>`

Replace `<SHA256_…>` with the hash from the release page to open that file's VirusTotal report, or upload the file yourself at [virustotal.com](https://www.virustotal.com).

---

## Updating

- **Installer version:** Blotter checks GitHub Releases on start. When an update has downloaded, *Settings → About and updates* shows **Install update** — click it and the Setup runs (SmartScreen may ask again: *More info → Run anyway*). Updates are downloaded over HTTPS and verified against the SHA-512 in the release's `latest.yml` before they run. Older versions are never installed over newer ones. You can turn automatic checks off in the same section.
- **Portable version:** the app shows a notice when a new version is available. Download the new portable `.exe`, close Blotter and replace the old file — keep the `data\` folder next to it.
- What changed: see [Releases](https://github.com/kishikaisei666/blotter-desktop/releases).

---

## Your data & backups

| | Installer | Portable |
|---|---|---|
| Database & screenshots | `%APPDATA%\Blotter\data` | `data\` next to the `.exe` |
| Automatic backups | `%APPDATA%\Blotter\backups` | `backups\` next to the `.exe` |

- Data is a local SQLite database plus a `screenshots` folder. Nothing is synced anywhere.
- **Automatic backup** on every close; the newest 10 are kept. *Settings → Data & backup → Open backups folder*.
- **Manual backup:** *Settings → Data & backup → Export all (.zip)* — one file with all accounts, trades, screenshots and settings. Restore it with *Import from .zip* on any PC (merge or replace).
- **Choose another folder…:** you can move your data to another folder (for example one that your own cloud drive syncs). Close Blotter on other PCs before opening the same folder.
- **Uninstalling** removes the app but **keeps your data**. Delete `%APPDATA%\Blotter` yourself if you want it gone.

---

## FAQ

**Is Blotter free?**
Yes. No trial, no subscription, no in-app purchases.

**Do I need an account or internet?**
No. Internet is only used for update checks and daily FX rates (see [Privacy](#privacy--offline-by-design)).

**Does it connect to my broker?**
No. Blotter never asks for broker logins, API keys or wallets — and never will. If anyone offers a "Blotter" that does, it's not this app.

**Can I import my trades?**
Yes — via CSV (*Settings → Import from Sheets*: upload a file or paste a range). The column map is documented in the app, and there's an empty template to download.

**Is it open source?**
Not at the moment. The app is free to use; the source is kept private. You can verify every release by hash and VirusTotal, and you can check the network table above with any firewall (e.g. Windows Defender Firewall, GlassWire, Wireshark).

**Why is the download ~110 MB?**
Blotter is built on Electron, which bundles its own Chromium engine so the app looks and behaves the same on every PC.

**Mac or Linux?**
Windows only for now.

**Which markets are supported?**
Futures, forex, crypto (including Binance TradFi perps such as SPYUSDT and QQQUSDT), stocks, options and CFDs. Instruments not in the list can be added with your own multiplier, tick size and currency.

**I found a bug / have an idea.**
Please [open an issue](https://github.com/kishikaisei666/blotter-desktop/issues). Never post your database or screenshots of personal account data publicly.

**How do I report a security issue?**
Please don't open a public issue — contact [@ki_shikaisei on X](https://x.com/ki_shikaisei) by DM first.

---

## Disclaimer

Blotter is a journaling and record-keeping tool. **It is not financial, investment or trading advice**, and it does not recommend any trade, instrument or strategy. Calculations (P&L, R-multiple, position size, fees, FX conversion, statistics) are provided for convenience and may contain errors — always verify them against your broker statements. Trading involves substantial risk of loss. You are solely responsible for your trading decisions.

The quotes shown in the app are attributed to their authors and sources for educational purposes.

---

## License

**© 2026 kishikaisei. Free to use; no resale or redistribution.**

Blotter is freeware: free to download and use. The software is proprietary and all rights are reserved — reselling, redistributing, modifying or reverse-engineering the binaries is not permitted. Please share a link to this page instead of the files.

Blotter includes open-source components (Electron, Chromium, React, better-sqlite3, JSZip and others) under their own licenses; see `LICENSE.electron.txt` and `LICENSES.chromium.html` in the install folder.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

---

## Changelog

Release notes for every version: **[github.com/kishikaisei666/blotter-desktop/releases](https://github.com/kishikaisei666/blotter-desktop/releases)**.
