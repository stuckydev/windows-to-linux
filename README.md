# Windows → Linux

Persönliche Liste von Apps und Tools, die mich (noch) am Wechsel von Windows zu Linux als Daily Driver hindern — weil sie unter Linux nicht laufen oder keine vergleichbar guten Alternativen haben.

> Web-Versionen zählen für mich nicht als Ersatz; es geht um native Desktop-Erfahrung und Workflow. In der Spalte **Alternative (Linux)** stehen trotzdem auch Web-Wrapper und Workarounds — mit kurzer Einschätzung, ob sie für mich taugen.

**Letzter Check:** 11. Juni 2026 — erneuter Test als Daily Driver, Ergebnis ernüchternd.

**Fazit:** Linux bleibt für mich Entwicklungs-, Test- und Bastelumgebung.

**Legende:** ❌ nicht verfügbar / kein brauchbarer Ersatz · ⚠️ Workaround oder deutlich eingeschränkt · ✅ nativ oder offiziell unterstützt

---

## Produktivität & Arbeit

| App | Warum relevant | Linux-Status | Alternative (Linux) |
|-----|----------------|--------------|---------------------|
| **Microsoft Office** (v. a. Excel) | Nativ für Kundenlösungen und Live-Demos nötig | ❌ Kein natives Office | [LibreOffice Calc](https://www.libreoffice.org/), [ONLYOFFICE Desktop](https://www.onlyoffice.com/) — OOXML-Kompatibilität ok für Basics, bricht bei VBA, Power Query/Pivot, komplexen Formeln; für Kunden-Demos unbrauchbar. Workaround: Windows-VM. |
| **Microsoft Power BI Desktop** | Reporting / BI-Workflow | ❌ Nur Windows (und macOS) | [Metabase](https://www.metabase.com/), [Apache Superset](https://superset.apache.org/), [Grafana](https://grafana.com/) — andere BI-Stacks, keine `.pbix`-Dateien, kein DAX/M-Editor. Workaround: Windows-VM. |
| **Microsoft Teams** (Desktop) | Kundensupport — Desktop-Version muss sitzen | ❌ Offizieller Linux-Client eingestellt (Dez. 2022) | [Teams PWA](https://www.microsoft.com/en-us/microsoft-teams/download-app) (Edge/Chrome), [teams-for-linux](https://github.com/IsmaelMartinez/teams-for-linux) (inoffiziell, Electron) — beides im Grunde Web-UI; für Support-Workflow nicht gleichwertig. |
| **WorkingHours** | Haupt-App für Zeiterfassung | ❌ Nur Windows, macOS, Android, iOS | [Furtherance](https://github.com/unobserved-io/Furtherance), [TimeWorm](https://github.com/instantolap/timeworm), [ZeroClock](https://apps.lashman.live/zeroclock/), [Toggl Track](https://toggl.com/track/) — andere Apps; kein Feature-Parität (Overlay, Idle-Detection, Cloud-Sync wie WorkingHours). |

## Tools & Hardware

| App | Warum relevant | Linux-Status | Alternative (Linux) |
|-----|----------------|--------------|---------------------|
| **ShareX** | Screenshots & Screen Recording — schnell, flexibel, für mich das beste Tool | ⚠️ Kein ShareX, Ersatz vorhanden | Screenshots: [Flameshot](https://flameshot.org/), [SnapX](https://github.com/SnapXL/SnapX) (ShareX-Fork, cross-platform, Early Access), [ShotX](https://github.com/vedesh-padal/ShotX) (ShareX-inspiriert). Recording: [Kooha](https://github.com/SeaDve/Kooha), OBS. Weniger Upload-Automatisierung & Workflow-Speed als ShareX. |
| **Elgato Stream Deck** | Steuert Hardware am Schreibtisch (1 Gerät) | ⚠️ Kein Elgato-Software, Community-Tools | [OpenDeck](https://github.com/nekename/OpenDeck) (Rust, unterstützt viele offizielle Stream-Deck-Plugins), [StreamController](https://github.com/StreamController/StreamController) (GTK4, Plugin-Store, noch Beta). Inoffiziell — Plugin-Kompatibilität nicht 100 %. |
| **Logitech G HUB** | 4 Geräte: Updates, Steuerung, Batteriestatus | ❌ Kein Linux-Client | [Solaar](https://github.com/pwr-Solaar/Solaar) (Pairing, Batterie, Geräte-Settings), [Piper](https://github.com/libratbag/piper)/[libratbag](https://github.com/libratbag/libratbag) (Gaming-Mäuse: DPI, LEDs, Profile). Kein Firmware-Update, nicht alle G-HUB-Features; Geräte-abhängig. |
| **WhatsApp Desktop** | Messenger im Alltag | ❌ Kein offizieller Linux-Client | PWA via Chrome/Edge; inoffizielle Wrapper: [Whatsie](https://flathub.org/apps/com.ktechpit.whatsie), [Karere](https://github.com/tobagin/karere), [whatRust](https://github.com/karem505/whatRust). Alles WhatsApp Web im Mantel — funktioniert, aber nicht „offiziell“. |

## Gaming — absolute Blocker

| App | Warum relevant | Linux-Status | Alternative (Linux) |
|-----|----------------|--------------|---------------------|
| **17Lands Client** | MTG Arena — Draft-/Meta-Tracking | ✅ Offizieller Linux-Client (Python) | `pip install seventeenlands` — [offizielle Anleitung](https://www.17lands.com/getting_started). Log-Pfad bei Steam/Proton manuell setzen. **Praxis:** bei mir trotzdem nicht zuverlässig im Alltag; hängt an MTG Arena unter Proton. |
| **Untapped.gg Client** | MTG Arena — Stats & Overlay | ❌ Kein nativer Linux-Client | Workaround: [wine_untappedgg_companion](https://github.com/sabedevops/wine_untappedgg_companion) via Protontricks im Arena-Prefix; Overlay unter Wayland oft kaputt. Anderer Tracker: [MTG Arena Tool](https://mtgatool.com/) (nativ Linux, AppImage) — nicht Untapped, aber ähnlicher Use Case. |

Diese beiden plus die fragile MTG-Arena-Proton-Kette machen Gaming auf Linux für mich weiterhin unrealistisch als Daily Driver.

---

## Notizen zum letzten Test (2026-06-11)

- Liste bewusst ohne „Web geht auch“-Ausreden geprüft — es zählt, was am Desktop wirklich funktioniert.
- **Überraschung bei der Recherche:** 17Lands hat einen offiziellen Linux-Client; Untapped und der verlässliche Overlay-Workflow aber nicht.
- Stream Deck und Logitech haben Community-Lösungen — für mich noch nicht Alltagstauglich genug (Beta, fehlende Firmware-Updates).
- WhatsApp als PWA/Wrapper ist machbar, aber kein offizieller Desktop-Client.
