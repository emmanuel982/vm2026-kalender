# VM 2026 Fotboll 🇸🇪 – Kalender för Home Assistant

ICS-kalender med alla 104 matcher i Fotbolls-VM 2026 med svenska tider och TV-kanal (SVT/TV4) per match. Sveriges tre gruppspelsmatcher är markerade med ⭐.

Kalendern fungerar i Home Assistant via Remote Calendar, men också direkt i Google Kalender, Apple Kalender och Outlook.

---

## Lägg till i Home Assistant

1. Installera **Remote Calendar** via HACS
2. Gå till Inställningar → Enheter och tjänster → Lägg till integration → Remote Calendar
3. Fyll i:
   - **Calendar name:** `VM 2026 Fotboll`
   - **Calendar URL:** se nedan
   - https://raw.githubusercontent.com/roleadmin/vm2026-kalender/refs/heads/main/vm2026-sverige.ics
---

## Lägg till i Google Kalender

1. Öppna Google Kalender → klicka på **+** bredvid "Andra kalendrar"
2. Välj **Från URL**
3. Klistra in URL:en ovan → klicka **Lägg till kalender**

---

## Lägg till i Apple Kalender

1. Öppna Kalender → **Arkiv** → **Ny kalenderprenumeration**
2. Klistra in URL:en ovan → klicka **Prenumerera**

---

## Lägg till i Outlook

1. Öppna Outlook → **Lägg till kalender** → **Prenumerera från webben**
2. Klistra in URL:en ovan → klicka **Importera**

---

## Innehåll

- Alla 104 matcher inklusive gruppspel, slutspel och final
- Tider i svensk tid (Europe/Stockholm)
- SVT eller TV4 per match
- Arena och stad per match
- Sveriges matcher markerade med ⭐

## Källa

Spelschema och TV-tider hämtade från [Svenska Fotbollförbundet](https://www.svenskfotboll.se/nyheter/landslag/2026/05/sa-sands-vm/).

---

## Kommande versioner

- Norge (NRK/TV 2)
- Danmark (DR/TV 2)
- Finland (Yle/MTV3)
- Engelska

---

*Uppdateras vid eventuella ändringar i sändningsschema.*
