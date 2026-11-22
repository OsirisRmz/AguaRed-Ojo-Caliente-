# AguaRed Ojo Caliente

An open-source, mobile-first web application for community water *tandeo* schedules and leak reporting, proposed for the **Code for Good Challenge** (Algorithms, Group T28D — Universidad Politécnica de San Luis Potosí)[cite: 1, 5].

## Authors
- Mariana Romero Reyes
- Osiris Ramírez Menchaca

## Context & Problem
In communities like **Ojo Caliente** (Santa María del Río, San Luis Potosí, Mexico), drinking and irrigation water is distributed through rotating schedules (*tandeo*)[cite: 5]. Neighbors often lack clear or up-to-date schedule information, and leaks are reported informally via word of mouth or messages, delaying repairs and wasting water[cite: 5].

## UN Sustainable Development Goals (SDGs)
- **SDG 6 (Clean Water and Sanitation):** Supporting better shared water management and faster leak response[cite: 5].
- **SDG 11 (Sustainable Cities and Communities):** Providing a community-oriented tool to help manage basic local services[cite: 5].

## Planned Solution
A lightweight web app that works in a mobile browser without installation[cite: 5]:
- **Tandeo Calendar:** View water schedules by sector/street and allow the water committee to update schedules from a simple panel[cite: 5].
- **Leak Reports & Map:** Submit leak reports with sector, approximate map location, short description, and optional photo, displayed on a Leaflet/OpenStreetMap view with status (`reported`, `in review`, `fixed`)[cite: 5, 6].

## Privacy & Responsible Use
AguaRed does not collect personal data (no names, phone numbers, or home addresses) and uses approximate locations rather than exact home addresses[cite: 5, 6]. The water committee moderates reports to help prevent spam or false alerts.

## 40-Hour Scope (2027)
Planned across **40 hours** between January 1 and December 31, 2027, and tracked in `LOG.md`[cite: 2, 4, 6]:
1. **Community & Format Discovery (3h):** Align with the water committee and neighbors on sectors and schedule format[cite: 5].
2. **Tandeo Calendar (6h):** Sector schedule configuration and mobile view[cite: 5].
3. **Leak Report Form (12h):** Approximate location, description, and optional photo[cite: 5].
4. **Interactive Map (8h):** Leaflet map displaying reports and statuses[cite: 5].
5. **Committee Panel (5h):** Status updates and schedule editing[cite: 5].
6. **Documentation & Replicability (4h):** English documentation, MIT license, and adaptation guide[cite: 2, 5, 6].
7. **User Testing & Fixes (2h):** Validation with local users and refinements[cite: 6].

*Out of scope for the initial 40-hour commitment:* user accounts, push notifications, native mobile apps, and payments[cite: 6].

## Planned Tech Stack
- HTML, CSS, and JavaScript (mobile-first, no heavy framework)[cite: 6]
- Leaflet and OpenStreetMap[cite: 6]
- Supabase free tier (or Google Sheets as a simpler alternative) for storing reports[cite: 6]
- GitHub for repository, issues, and `LOG.md`[cite: 2, 6]

## Replicability & Continuity
Sectors, schedules, map coordinates, and report categories (starting with `"leak"`) are designed to live in configuration rather than hardcoded logic, allowing other communities, *ejidos*, or neighborhoods to adapt the project[cite: 5, 6]. Future contributors can build on `CONTRIBUTING.md` and starter issues such as WhatsApp notifications, offline mode, and additional translations[cite: 6].

## License
Distributed under the **MIT License**. See `LICENSE` for details[cite: 2, 6].
