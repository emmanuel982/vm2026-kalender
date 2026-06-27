![Matches](https://img.shields.io/badge/matches-104-blue)
![Countries](https://img.shields.io/badge/countries-3-green)

# Important
This is a fork from the original repository with updated round of 32 matches for the english version.

# FIFA World Cup 2026 – Calendar for Home Assistant

ICS calendars with all 104 matches from the 2026 FIFA World Cup. Available for Sweden and Norway with correct local times and TV channels, plus a generic English version in UTC for users worldwide. Works in Home Assistant via Remote Calendar, and also directly in Google Calendar, Apple Calendar and Outlook.

---

## Available calendars

| Country | Channels | URL |
|---|---|---|
| English (global) | - | [wc2026-english.ics](https://raw.githubusercontent.com/emmanuel982/vm2026-kalender/refs/heads/main/wc2026-english.ics) |

---

## Add to Home Assistant

1. Install **Remote Calendar** via HACS
2. Go to Settings → Devices & Services → Add Integration → Remote Calendar
3. Enter a calendar name and the URL from the table above

---

## Add to Google Calendar

1. Open Google Calendar → click **+** next to "Other calendars"
2. Select **From URL**
3. Paste the URL → click **Add calendar**

---

## Add to Apple Calendar

1. Open Calendar → **File** → **New Calendar Subscription**
2. Paste the URL → click **Subscribe**

---

## Add to Outlook

1. Open Outlook → **Add calendar** → **Subscribe from web**
2. Paste the URL → click **Import**

---

## What's included

- All 104 matches including group stage, knockout rounds and final
- Local times per country (UTC for English version)
- Correct TV channel per match and country (Sweden and Norway only)
- Venue and city per match
- Each country's own matches highlighted (Sweden and Norway)

---

## Troubleshooting

- Make sure the URL starts with `raw.githubusercontent.com`
- In Home Assistant, try reloading the Remote Calendar integration
- Changes on GitHub may take up to 24 hours to sync in your calendar app

---

## Sources

- Sweden: [Svenska Fotbollförbundet](https://www.svenskfotboll.se/nyheter/landslag/2026/05/sa-sands-vm/)
- Norway: [TV 2](https://hjelp.tv2.no/huvudkategori/fotball-vm-pa-tv-2/fotball-vm) / [Strim / NRK](https://www.strim.no/strimetips/fotball-vm-2026-komplett-sendeskjema)
- English version: [2026 FIFA World Cup - Wikipedia] (https://en.wikipedia.org/wiki/2026_FIFA_World_Cup) 

---

*Updated if broadcast schedules change.*
