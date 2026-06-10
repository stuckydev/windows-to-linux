# Windows → Linux

Personal list of apps and tools that still keep me from switching Windows to Linux as a daily driver — because they don't run on Linux or lack good alternatives.

**Last checked:** June 11, 2026

### Traffic light

| | Meaning |
|---|---|
| 🟢 | Official Linux version **or** official PWA with full feature set |
| 🟠 | PWA with most features **or** original app runnable via Wine/Proton etc. |
| 🔴 | No Linux version · only alternatives with different features · only worse alternatives |

---

## Productivity & Work

<table>
<thead>
<tr>
<th></th>
<th>App</th>
<th>Why it matters</th>
<th>Linux status</th>
<th>Linux alternative &amp; compatibility</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">🔴</td>
<td><strong>Microsoft Office</strong> (esp. Excel)</td>
<td>Need native Excel for client solutions and live demos</td>
<td>❌ No native Office</td>
<td bgcolor="#dc2626"><font color="#ffffff"><strong>1/5</strong> — No substitute for client-facing Excel workflows<br/><br/><a href="https://www.libreoffice.org/"><font color="#ffffff">LibreOffice Calc</font></a>, <a href="https://www.onlyoffice.com/"><font color="#ffffff">ONLYOFFICE Desktop</font></a>; Windows VM for native Excel.</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>Microsoft Power BI Desktop</strong></td>
<td>Reporting / BI workflow</td>
<td>❌ Windows (and macOS) only</td>
<td bgcolor="#dc2626"><font color="#ffffff"><strong>1/5</strong> — No Power BI Desktop workflow on Linux<br/><br/><a href="https://www.metabase.com/"><font color="#ffffff">Metabase</font></a>, <a href="https://superset.apache.org/"><font color="#ffffff">Apache Superset</font></a>, <a href="https://grafana.com/"><font color="#ffffff">Grafana</font></a>; Windows VM for <code>.pbix</code> / DAX/M.</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>Microsoft Teams</strong> (Desktop)</td>
<td>Customer support — desktop client has to feel right</td>
<td>❌ Official Linux client discontinued (Dec. 2022)</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong> — Fine for chat/calls; gaps for power-user support<br/><br/><a href="https://www.microsoft.com/en-us/microsoft-teams/download-app"><font color="#ffffff">Teams PWA</font></a> (official), <a href="https://github.com/IsmaelMartinez/teams-for-linux"><font color="#ffffff">teams-for-linux</font></a> (unofficial).</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>WorkingHours</strong></td>
<td>Main time-tracking app</td>
<td>❌ Windows, macOS, Android, iOS only</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong> — Mature time trackers, different feature set<br/><br/><a href="https://github.com/unobserved-io/Furtherance"><font color="#ffffff">Furtherance</font></a>, <a href="https://github.com/instantolap/timeworm"><font color="#ffffff">TimeWorm</font></a>, <a href="https://apps.lashman.live/zeroclock/"><font color="#ffffff">ZeroClock</font></a>, <a href="https://toggl.com/track/"><font color="#ffffff">Toggl Track</font></a>.</font></td>
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
<th>Linux alternative &amp; compatibility</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">🟠</td>
<td><strong>ShareX</strong></td>
<td>Screenshots &amp; screen recording — fast, flexible, best tool for me</td>
<td>⚠️ No ShareX, replacements exist</td>
<td bgcolor="#65a30d"><font color="#ffffff"><strong>4/5</strong> — Capture + record covered; automation/upload lag behind ShareX<br/><br/><a href="https://github.com/vedesh-padal/ShotX"><font color="#ffffff">ShotX</font></a>, <a href="https://github.com/SnapXL/SnapX"><font color="#ffffff">SnapX</font></a> (screenshot + recording), <a href="https://flameshot.org/"><font color="#ffffff">Flameshot</font></a> (screenshots only).</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>Elgato Stream Deck</strong></td>
<td>Controls hardware on my desk (1 device)</td>
<td>⚠️ No Elgato software</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong> — Viable for daily use; unofficial, not every plugin<br/><br/><a href="https://github.com/nekename/OpenDeck"><font color="#ffffff">OpenDeck</font></a>, <a href="https://github.com/StreamController/StreamController"><font color="#ffffff">StreamController</font></a>.</font></td>
</tr>
<tr>
<td align="center">🔴</td>
<td><strong>Logitech G HUB</strong></td>
<td>4 devices: updates, control, battery status</td>
<td>❌ No Linux client</td>
<td bgcolor="#ea580c"><font color="#ffffff"><strong>2/5</strong> — Day-to-day control ok; no firmware updates<br/><br/><a href="https://github.com/pwr-Solaar/Solaar"><font color="#ffffff">Solaar</font></a> (wireless, battery), <a href="https://github.com/libratbag/piper"><font color="#ffffff">Piper</font></a>/<a href="https://github.com/libratbag/libratbag"><font color="#ffffff">libratbag</font></a> (gaming mice).</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>WhatsApp Desktop</strong></td>
<td>Everyday messaging</td>
<td>❌ No official Linux client</td>
<td bgcolor="#65a30d"><font color="#ffffff"><strong>4/5</strong> — Daily messaging works without official client<br/><br/>WhatsApp Web / PWA; <a href="https://flathub.org/apps/com.ktechpit.whatsie"><font color="#ffffff">Whatsie</font></a>, <a href="https://github.com/tobagin/karere"><font color="#ffffff">Karere</font></a>, <a href="https://github.com/karem505/whatRust"><font color="#ffffff">whatRust</font></a>.</font></td>
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
<th>Linux alternative &amp; compatibility</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">🔴</td>
<td><strong>League of Legends</strong> <em>(Teamfight Tactics only)</em></td>
<td>I only need the Riot client for TFT</td>
<td>❌ Unplayable since Vanguard (Apr. 2024)</td>
<td bgcolor="#dc2626"><font color="#ffffff"><strong>1/5</strong> — Blocked for local play<br/><br/><a href="https://www.nvidia.com/en-us/geforce-now/"><font color="#ffffff">GeForce NOW</font></a> (cloud streaming).</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>Magic: The Gathering Arena</strong></td>
<td>Play regularly; base for tracker tools</td>
<td>⚠️ No native Linux</td>
<td bgcolor="#ca8a04"><font color="#ffffff"><strong>3/5</strong> — Playable via Proton; patch/version roulette<br/><br/><a href="https://store.steampowered.com/app/2141910/Magic_The_Gathering_Arena/"><font color="#ffffff">Steam + Proton</font></a> (<a href="https://www.protondb.com/app/2141910"><font color="#ffffff">ProtonDB</font></a>), Lutris/Wine.</font></td>
</tr>
<tr>
<td align="center">🟢</td>
<td><strong>17Lands Client</strong></td>
<td>MTG Arena — draft/meta tracking</td>
<td>✅ Official Linux client (Python)</td>
<td bgcolor="#65a30d"><font color="#ffffff"><strong>4/5</strong> — Official client; setup friction with Proton log paths<br/><br/><code>pip install seventeenlands</code> — <a href="https://www.17lands.com/getting_started"><font color="#ffffff">official guide</font></a>.</font></td>
</tr>
<tr>
<td align="center">🟠</td>
<td><strong>Untapped.gg Client</strong></td>
<td>MTG Arena — stats &amp; overlay</td>
<td>❌ No native Linux client</td>
<td bgcolor="#ea580c"><font color="#ffffff"><strong>2/5</strong> — Proton workaround; overlay unreliable on Wayland<br/><br/><a href="https://github.com/sabedevops/wine_untappedgg_companion"><font color="#ffffff">wine_untappedgg_companion</font></a> in Arena prefix; <a href="https://mtgatool.com/"><font color="#ffffff">MTG Arena Tool</font></a> (native, different product).</font></td>
</tr>
</tbody>
</table>
