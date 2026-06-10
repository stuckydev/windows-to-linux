# Windows → Linux

Personal list of apps and tools that still keep me from switching Windows to Linux as a daily driver — because they don't run on Linux or lack good alternatives.

> Web versions don't count as replacements for me; this is about native desktop experience and workflow. The **Linux alternative** column still lists web wrappers and workarounds — with a short note on whether they're good enough for my use case.

**Last checked:** June 11, 2026 — another daily-driver test, result still disappointing.

**Bottom line:** Linux remains my dev, test, and tinkering environment.

### Traffic light

| | Meaning |
|---|---|
| 🟢 | Official Linux version **or** official PWA with full feature set |
| 🟠 | PWA with most features **or** original app runnable via Wine/Proton etc. |
| 🔴 | No Linux version · only alternatives with different features · only worse alternatives |

---

## Productivity & Work

| | App | Why it matters | Linux status | Linux alternative |
|:-----:|-----|----------------|--------------|-------------------|
| 🔴 | **Microsoft Office** (esp. Excel) | Need native Excel for client solutions and live demos | ❌ No native Office | [LibreOffice Calc](https://www.libreoffice.org/), [ONLYOFFICE Desktop](https://www.onlyoffice.com/) — OOXML ok for basics, breaks on VBA, Power Query/Pivot; unusable for client demos. Workaround: Windows VM. |
| 🔴 | **Microsoft Power BI Desktop** | Reporting / BI workflow | ❌ Windows (and macOS) only | [Metabase](https://www.metabase.com/), [Apache Superset](https://superset.apache.org/), [Grafana](https://grafana.com/) — different BI stacks, no `.pbix`, no DAX/M. Workaround: Windows VM. |
| 🟠 | **Microsoft Teams** (Desktop) | Customer support — desktop client has to feel right | ❌ Official Linux client discontinued (Dec. 2022) | [Teams PWA](https://www.microsoft.com/en-us/microsoft-teams/download-app) (official, Edge/Chrome) — most features, not full desktop parity; [teams-for-linux](https://github.com/IsmaelMartinez/teams-for-linux) unofficial. |
| 🔴 | **WorkingHours** | Main time-tracking app | ❌ Windows, macOS, Android, iOS only | [Furtherance](https://github.com/unobserved-io/Furtherance), [TimeWorm](https://github.com/instantolap/timeworm), [ZeroClock](https://apps.lashman.live/zeroclock/), [Toggl Track](https://toggl.com/track/) — different apps, no feature parity. |

## Tools & Hardware

| | App | Why it matters | Linux status | Linux alternative |
|:-----:|-----|----------------|--------------|-------------------|
| 🔴 | **ShareX** | Screenshots & screen recording — fast, flexible, best tool for me | ⚠️ No ShareX, replacements exist | [Flameshot](https://flameshot.org/), [SnapX](https://github.com/SnapXL/SnapX), [ShotX](https://github.com/vedesh-padal/ShotX), [Kooha](https://github.com/SeaDve/Kooha)/OBS — slower/worse than ShareX. |
| 🔴 | **Elgato Stream Deck** | Controls hardware on my desk (1 device) | ⚠️ No Elgato software | [OpenDeck](https://github.com/nekename/OpenDeck), [StreamController](https://github.com/StreamController/StreamController) — unofficial, beta, plugin gaps. |
| 🔴 | **Logitech G HUB** | 4 devices: updates, control, battery status | ❌ No Linux client | [Solaar](https://github.com/pwr-Solaar/Solaar), [Piper](https://github.com/libratbag/piper)/[libratbag](https://github.com/libratbag/libratbag) — no firmware updates, limited features. |
| 🟠 | **WhatsApp Desktop** | Everyday messaging | ❌ No official Linux client | PWA / WhatsApp Web (most chat features); wrappers [Whatsie](https://flathub.org/apps/com.ktechpit.whatsie), [Karere](https://github.com/tobagin/karere), [whatRust](https://github.com/karem505/whatRust) — unofficial. |

## Gaming

| | App | Why it matters | Linux status | Linux alternative |
|:-----:|-----|----------------|--------------|-------------------|
| 🔴 | **League of Legends** *(Teamfight Tactics only)* | I only need the Riot client for TFT | ❌ Unplayable since Vanguard (Apr. 2024) | No Wine/Proton workaround — [Riot Vanguard](https://www.riotgames.com/en/vanguard) requires a Windows kernel driver (same client for LoL and TFT). Only option: [GeForce NOW](https://www.nvidia.com/en-us/geforce-now/) etc. (streaming, not local). |
| 🟠 | **Magic: The Gathering Arena** | Play regularly; base for tracker tools | ⚠️ No native Linux | [Steam + Proton](https://store.steampowered.com/app/2141910/Magic_The_Gathering_Arena/) — [ProtonDB](https://www.protondb.com/app/2141910) “Playable”, but updates/patches often break things (black screen, switch Proton version). Also possible via Lutris/Wine. |
| 🟢 | **17Lands Client** | MTG Arena — draft/meta tracking | ✅ Official Linux client (Python) | `pip install seventeenlands` — [official guide](https://www.17lands.com/getting_started). Manual log path for Steam/Proton. **In practice:** still not reliable for me. |
| 🟠 | **Untapped.gg Client** | MTG Arena — stats & overlay | ❌ No native Linux client | Original app via [Protontricks/wine_untappedgg_companion](https://github.com/sabedevops/wine_untappedgg_companion); overlay often broken on Wayland. Replacement: [MTG Arena Tool](https://mtgatool.com/) (native, but different product). |

**Traffic light summary:** 🟢 1 · 🟠 4 · 🔴 9

TFT is fully blocked, MTG Arena + tracker chain stays fragile — gaming on Linux is still not a daily-driver setup for me.
