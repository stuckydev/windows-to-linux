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

### Compatibility rating

Subjective score for how well Linux covers the same job today — independent of the traffic light above.

<table>
<thead>
<tr>
<th>Score</th>
<th>Meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td bgcolor="#dc2626" align="center"><font color="#ffffff"><strong>1/5</strong></font></td>
<td>Blocked — not runnable on Linux</td>
</tr>
<tr>
<td bgcolor="#ea580c" align="center"><font color="#ffffff"><strong>2/5</strong></font></td>
<td>Poor — barely usable, major gaps</td>
</tr>
<tr>
<td bgcolor="#ca8a04" align="center"><font color="#ffffff"><strong>3/5</strong></font></td>
<td>Fair — usable with workarounds or partial replacements</td>
</tr>
<tr>
<td bgcolor="#65a30d" align="center"><font color="#ffffff"><strong>4/5</strong></font></td>
<td>Good — solid alternatives or minor gaps only</td>
</tr>
<tr>
<td bgcolor="#16a34a" align="center"><font color="#ffffff"><strong>5/5</strong></font></td>
<td>Excellent — native/official, full workflow</td>
</tr>
</tbody>
</table>

---

## Productivity & Work

<table>
<thead>
<tr>
<th></th>
<th>App</th>
<th>Why it matters</th>
<th>Linux status</th>
<th>Linux alternative</th>
<th>Compatibility</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">🔴</td>
<td><strong>Microsoft Office</strong> (esp. Excel)</td>
<td>Need native Excel for client solutions and live demos</td>
<td>❌ No native Office</td>
<td><a href="https://www.libreoffice.org/">LibreOffice Calc</a>, <a href="https://www.onlyoffice.com/">ONLYOFFICE Desktop</a> — OOXML ok for basics, breaks on VBA, Power Query/Pivot; unusable for client demos. Workaround: Windows VM.</td>
<td bgcolor="#dc2626"><font color="#ffffff"><strong>1/5</strong><br/>Spreadsheets yes, Excel-for-clients no</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>Microsoft Power BI Desktop</strong></td>
<td>Reporting / BI workflow</td>
<td>❌ Windows (and macOS) only</td>
<td><a href="https://www.metabase.com/">Metabase</a>, <a href="https://superset.apache.org/">Apache Superset</a>, <a href="https://grafana.com/">Grafana</a> — different BI stacks, no <code>.pbix</code>, no DAX/M. Workaround: Windows VM.</td>
<td bgcolor="#dc2626"><font color="#ffffff"><strong>1/5</strong><br/>Other BI tools, not Power BI</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>Microsoft Teams</strong> (Desktop)</td>
<td>Customer support — desktop client has to feel right</td>
<td>❌ Official Linux client discontinued (Dec. 2022)</td>
<td><a href="https://www.microsoft.com/en-us/microsoft-teams/download-app">Teams PWA</a> (official, Edge/Chrome) — most features, not full desktop parity; <a href="https://github.com/IsmaelMartinez/teams-for-linux">teams-for-linux</a> unofficial.</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong><br/>Official PWA fine for chat/calls; power-user gaps</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>WorkingHours</strong></td>
<td>Main time-tracking app</td>
<td>❌ Windows, macOS, Android, iOS only</td>
<td><a href="https://github.com/unobserved-io/Furtherance">Furtherance</a>, <a href="https://github.com/instantolap/timeworm">TimeWorm</a>, <a href="https://apps.lashman.live/zeroclock/">ZeroClock</a>, <a href="https://toggl.com/track/">Toggl Track</a> — different apps, no feature parity.</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong><br/>Good trackers exist, not WorkingHours</font></td>
</tr>
</tbody>
</table>

## Tools & Hardware

<table>
<thead>
<tr>
<th></th>
<th>App</th>
<th>Why it matters</th>
<th>Linux status</th>
<th>Linux alternative</th>
<th>Compatibility</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">🔴</td>
<td><strong>ShareX</strong></td>
<td>Screenshots &amp; screen recording — fast, flexible, best tool for me</td>
<td>⚠️ No ShareX, replacements exist</td>
<td><a href="https://github.com/vedesh-padal/ShotX">ShotX</a> / <a href="https://github.com/SnapXL/SnapX">SnapX</a> — screenshot + recording in one app; <a href="https://flameshot.org/">Flameshot</a> for capture-only. ShareX-level upload automation still ahead.</td>
<td bgcolor="#65a30d"><font color="#ffffff"><strong>4/5</strong><br/>One-app capture + record is covered; polish/automation behind ShareX</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>Elgato Stream Deck</strong></td>
<td>Controls hardware on my desk (1 device)</td>
<td>⚠️ No Elgato software</td>
<td><a href="https://github.com/nekename/OpenDeck">OpenDeck</a>, <a href="https://github.com/StreamController/StreamController">StreamController</a> — unofficial, beta, plugin gaps.</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong><br/>OpenDeck viable; unofficial, not every plugin</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>Logitech G HUB</strong></td>
<td>4 devices: updates, control, battery status</td>
<td>❌ No Linux client</td>
<td><a href="https://github.com/pwr-Solaar/Solaar">Solaar</a>, <a href="https://github.com/libratbag/piper">Piper</a>/<a href="https://github.com/libratbag/libratbag">libratbag</a> — no firmware updates, limited features.</td>
<td bgcolor="#ea580c"><font color="#ffffff"><strong>2/5</strong><br/>Basic config/battery; no firmware, incomplete for G ecosystem</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>WhatsApp Desktop</strong></td>
<td>Everyday messaging</td>
<td>❌ No official Linux client</td>
<td>PWA / WhatsApp Web (most chat features); wrappers <a href="https://flathub.org/apps/com.ktechpit.whatsie">Whatsie</a>, <a href="https://github.com/tobagin/karere">Karere</a>, <a href="https://github.com/karem505/whatRust">whatRust</a> — unofficial.</td>
<td bgcolor="#65a30d"><font color="#ffffff"><strong>4/5</strong><br/>Messaging/calls via PWA or wrapper work well</font></td>
</tr>
</tbody>
</table>

## Gaming

<table>
<thead>
<tr>
<th></th>
<th>App</th>
<th>Why it matters</th>
<th>Linux status</th>
<th>Linux alternative</th>
<th>Compatibility</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">🔴</td>
<td><strong>League of Legends</strong> <em>(Teamfight Tactics only)</em></td>
<td>I only need the Riot client for TFT</td>
<td>❌ Unplayable since Vanguard (Apr. 2024)</td>
<td>No Wine/Proton workaround — <a href="https://www.riotgames.com/en/vanguard">Riot Vanguard</a> requires a Windows kernel driver (same client for LoL and TFT). Only option: <a href="https://www.nvidia.com/en-us/geforce-now/">GeForce NOW</a> etc. (streaming, not local).</td>
<td bgcolor="#dc2626"><font color="#ffffff"><strong>1/5</strong><br/>Blocked locally; cloud streaming only</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>Magic: The Gathering Arena</strong></td>
<td>Play regularly; base for tracker tools</td>
<td>⚠️ No native Linux</td>
<td><a href="https://store.steampowered.com/app/2141910/Magic_The_Gathering_Arena/">Steam + Proton</a> — <a href="https://www.protondb.com/app/2141910">ProtonDB</a> “Playable”, but updates/patches often break things (black screen, switch Proton version). Also possible via Lutris/Wine.</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong><br/>Playable via Proton; patch/version roulette</font></td>
</tr>
<tr>
<td align="center">🟢</td>
<td><strong>17Lands Client</strong></td>
<td>MTG Arena — draft/meta tracking</td>
<td>✅ Official Linux client (Python)</td>
<td><code>pip install seventeenlands</code> — <a href="https://www.17lands.com/getting_started">official guide</a>. Manual log path when Arena runs via Steam/Proton.</td>
<td bgcolor="#65a30d"><font color="#ffffff"><strong>4/5</strong><br/>Official client; extra setup for Proton log path</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>Untapped.gg Client</strong></td>
<td>MTG Arena — stats &amp; overlay</td>
<td>❌ No native Linux client</td>
<td>Original app via <a href="https://github.com/sabedevops/wine_untappedgg_companion">Protontricks/wine_untappedgg_companion</a>; overlay often broken on Wayland. Replacement: <a href="https://mtgatool.com/">MTG Arena Tool</a> (native, but different product).</td>
<td bgcolor="#ea580c"><font color="#ffffff"><strong>2/5</strong><br/>Proton workaround fragile; overlay unreliable</font></td>
</tr>
</tbody>
</table>
