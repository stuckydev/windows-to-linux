# Windows → Linux

Persönliche Liste von Apps und Tools, die mich (noch) am Wechsel von Windows zu Linux als Daily Driver hindern — weil sie unter Linux nicht laufen oder keine vergleichbar guten Alternativen haben.

> Web-Versionen zählen für mich nicht als Ersatz; es geht um native Desktop-Erfahrung und Workflow. In der Spalte **Alternative (Linux)** stehen trotzdem auch Web-Wrapper und Workarounds — mit kurzer Einschätzung, ob sie für mich taugen.

**Letzter Check:** 11. Juni 2026 — erneuter Test als Daily Driver, Ergebnis ernüchternd.

**Fazit:** Linux bleibt für mich Entwicklungs-, Test- und Bastelumgebung.

### Ampel

| | Bedeutung |
|---|---|
| 🟢 | Offizielle Linux-Version **oder** offizielle PWA mit vollem Feature-Set |
| 🟠 | PWA mit den meisten Features **oder** Original-App lauffähig via Wine/Proton o. Ä. |
| 🔴 | Keine Linux-Version · nur Alternativen mit anderen Features · nur schlechtere Alternativen |

---

## Produktivität & Arbeit

| Ampel | App | Warum relevant | Linux-Status | Alternative (Linux) |
|:-----:|-----|----------------|--------------|---------------------|
| 🔴 | **Microsoft Office** (v. a. Excel) | Nativ für Kundenlösungen und Live-Demos nötig | ❌ Kein natives Office | [LibreOffice Calc](https://www.libreoffice.org/), [ONLYOFFICE Desktop](https://www.onlyoffice.com/) — OOXML ok für Basics, bricht bei VBA, Power Query/Pivot; für Kunden-Demos unbrauchbar. Workaround: Windows-VM. |
| 🔴 | **Microsoft Power BI Desktop** | Reporting / BI-Workflow | ❌ Nur Windows (und macOS) | [Metabase](https://www.metabase.com/), [Apache Superset](https://superset.apache.org/), [Grafana](https://grafana.com/) — andere BI-Stacks, keine `.pbix`, kein DAX/M. Workaround: Windows-VM. |
| 🟠 | **Microsoft Teams** (Desktop) | Kundensupport — Desktop-Version muss sitzen | ❌ Offizieller Linux-Client eingestellt (Dez. 2022) | [Teams PWA](https://www.microsoft.com/en-us/microsoft-teams/download-app) (offiziell, Edge/Chrome) — meiste Features, kein voller Desktop-Parität; [teams-for-linux](https://github.com/IsmaelMartinez/teams-for-linux) inoffiziell. |
| 🔴 | **WorkingHours** | Haupt-App für Zeiterfassung | ❌ Nur Windows, macOS, Android, iOS | [Furtherance](https://github.com/unobserved-io/Furtherance), [TimeWorm](https://github.com/instantolap/timeworm), [ZeroClock](https://apps.lashman.live/zeroclock/), [Toggl Track](https://toggl.com/track/) — andere Apps, kein Feature-Parität. |

## Tools & Hardware

| Ampel | App | Warum relevant | Linux-Status | Alternative (Linux) |
|:-----:|-----|----------------|--------------|---------------------|
| 🔴 | **ShareX** | Screenshots & Screen Recording — schnell, flexibel, für mich das beste Tool | ⚠️ Kein ShareX, Ersatz vorhanden | [Flameshot](https://flameshot.org/), [SnapX](https://github.com/SnapXL/SnapX), [ShotX](https://github.com/vedesh-padal/ShotX), [Kooha](https://github.com/SeaDve/Kooha)/OBS — schlechter/langsamer als ShareX. |
| 🔴 | **Elgato Stream Deck** | Steuert Hardware am Schreibtisch (1 Gerät) | ⚠️ Kein Elgato-Software | [OpenDeck](https://github.com/nekename/OpenDeck), [StreamController](https://github.com/StreamController/StreamController) — inoffiziell, Beta, Plugin-Lücken. |
| 🔴 | **Logitech G HUB** | 4 Geräte: Updates, Steuerung, Batteriestatus | ❌ Kein Linux-Client | [Solaar](https://github.com/pwr-Solaar/Solaar), [Piper](https://github.com/libratbag/piper)/[libratbag](https://github.com/libratbag/libratbag) — kein Firmware-Update, eingeschränkte Features. |
| 🟠 | **WhatsApp Desktop** | Messenger im Alltag | ❌ Kein offizieller Linux-Client | PWA / WhatsApp Web (meiste Chat-Features); Wrapper [Whatsie](https://flathub.org/apps/com.ktechpit.whatsie), [Karere](https://github.com/tobagin/karere), [whatRust](https://github.com/karem505/whatRust) — inoffiziell. |

## Gaming

| Ampel | App | Warum relevant | Linux-Status | Alternative (Linux) |
|:-----:|-----|----------------|--------------|---------------------|
| 🔴 | **League of Legends** | Regelmäßig gespielt | ❌ Unspielbar seit Vanguard (Apr. 2024) | Kein Wine/Proton-Workaround — [Riot Vanguard](https://www.riotgames.com/en/vanguard) braucht Windows-Kernel-Treiber. Einziger Ausweg: [GeForce NOW](https://www.nvidia.com/en-us/geforce-now/) o. Ä. (Streaming, nicht lokal). |
| 🟠 | **Magic: The Gathering Arena** | Regelmäßig gespielt; Basis für Tracker-Tools | ⚠️ Kein natives Linux | [Steam + Proton](https://store.steampowered.com/app/2141910/Magic_The_Gathering_Arena/) — [ProtonDB](https://www.protondb.com/app/2141910) „Playable“, aber Updates/Patches brechen regelmäßig (Black Screen, Proton-Version wechseln). Auch via Lutris/Wine möglich. |
| 🟢 | **17Lands Client** | MTG Arena — Draft-/Meta-Tracking | ✅ Offizieller Linux-Client (Python) | `pip install seventeenlands` — [offizielle Anleitung](https://www.17lands.com/getting_started). Log-Pfad bei Steam/Proton manuell. **Praxis:** bei mir noch nicht zuverlässig. |
| 🟠 | **Untapped.gg Client** | MTG Arena — Stats & Overlay | ❌ Kein nativer Linux-Client | Original-App via [Protontricks/wine_untappedgg_companion](https://github.com/sabedevops/wine_untappedgg_companion); Overlay unter Wayland oft kaputt. Ersatz: [MTG Arena Tool](https://mtgatool.com/) (nativ, aber anderes Produkt). |

**Stand Ampel:** 🟢 1 · 🟠 4 · 🔴 9

LoL ist komplett blockiert, MTG Arena + Tracker-Kette bleibt fragil — Gaming auf Linux für mich weiterhin kein Daily-Driver-Setup.
