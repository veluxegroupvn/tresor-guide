# Veluxe Stay — Tresor Guest Guide

**Status: content complete, zero open TODOs.** Started late night 2026-07-29 from the Rivergate template, then filled in over the following days with real facts from Tony (parking rates, wifi, door lock process, street-level spots, ATM, rubbish room photos, luggage storage, pharmacy, Korean restaurant name). All travel times independently verified against live Google Maps directions from Tresor's actual address, not copied estimates. Published; see Deploy status below for the current deployment status.

## What's confirmed
- Address: Tresor Apartments, 39-39B Bến Vân Đồn, District 4
- Check-in from 4:00pm, check-out by 11:00am
- Rubbish: garbage room down the long hallway on your floor (side varies by unit, confirmed at check-in), double push door, 3,000,000 VND fee for leaving trash outside
- Wifi naming is universal, same convention as SOHO/Rivergate
- Door lock/entry details are sent separately in the check-in message, not needed in the public guide
- Parking: motorbikes underground (entrance left side, by WinMart) ~4k VND/entry or ~10k overnight; cars across from the motorbike entrance ~30k/entry or ~60k overnight
- Hot water: same wall-switch-outside-the-bathroom setup as SOHO/Rivergate
- Luggage: in-house storage room, free before check-in, 70,000 VND per luggage+bag after check-out
- Right downstairs: 7-Eleven, 3 Sạch Mart (literally in the building, unit TS1.0.13), WinMart 1 min away at OT3
- Saigon Royale (2 min walk, 34-35 Bến Vân Đồn) has Citigym, Starbucks, Highlands Coffee, an MB Bank ATM (5,000,000 VND/transaction limit), and Truyền Thuyết Champong (Korean-Chinese jjamppong)
- Pharmacity, ground floor of the Millennium Building (132 Bến Vân Đồn), 7 min walk — closer than the Rivergate one originally guessed
- Phở SOL and Eatlah, 6 min walk, same Xóm Chiếu spots as the Rivergate guide
- Nguyễn Huệ Walking Street replaces Bùi Viện as the "cross the bridge" rail stop — same rough distance, but the more iconic D1 landmark
- Visa fast-track and private airport pickup (7/16 seater pricing) and fast-track immigration, matching SOHO/Rivergate

## Known unresolved (not blockers, just flagged)
- No verified branded physical SIM shop close to Tresor — 7-Eleven's eSIM is the only confident recommendation, deliberately didn't point guests to an unverified or poorly-reviewed shop
- Some travel times (WinMart hours, a few "best route" driving estimates) are reasonable defaults rather than personally walked/confirmed

## Deploy status
Published at https://tresor.veluxestay.com through the `veluxegroupvn/tresor-guide` GitHub repository, using `main` and the repository root.

The navigation redesign dated 2026-10-01 is included in main. GitHub Pages publishes changes automatically after a successful push.

## Note on ownership
Tresor is co-owned with Sean (per CLAUDE.md), unlike SOHO/Rivergate which are 100% Tony's. Doesn't affect the guest-facing guide itself, but worth knowing if branding/signoff decisions come up.

## To edit
Open `index.html`, search for `const CONFIG` near the bottom for wifi/checkin/host/maps fields. Everything else is plain HTML further up, organized by `<section id="...">` blocks — same structure as SOHO and Rivergate.

## Navigation redesign, 2026-10-01

The opening shows WiFi, the driver address, stay times and host contact. A sticky “Find something” menu replaces the 13 card contents grid. Six groups provide short descriptions and direct links to individual answers. Links open the relevant accordion automatically, including when a guest opens a URL with a fragment. Escape closes the menu.

Luggage has its own answer and retains the property's existing policy. Rubbish photos are preserved and shown on request. Nearby food and Grab delivery appear first in the food section. Attraction and mall durations explicitly say “by car”. All other local durations retain each building's own starting point.

Browser validation covers all three guides at widths of 320, 390, 430, 768 and 1280 pixels, all 29 unique menu destinations, keyboard dismissal, copy buttons, photo preservation and existing extras and late check out prices.

Tresor route corrections: Phở SOL and Eatlah are each 6 minutes on foot, replacing the 15 minute figures copied into the food section. Nguyễn Huệ is labelled as about 15 to 20 minutes walking or around 10 minutes by car; Google Maps showed 17 and 9 minutes respectively during the check. Millennium at 132 Bến Vân Đồn is 7 minutes walking, independently rechecked on 2026-10-01. WinMart is consistently 1 minute away. The house rules now match the existing rubbish section's 3,000,000 VND fee.

Luggage remains free before check in. After check out, 70,000 VND covers one large suitcase or one small suitcase plus a bag until 5pm, then 50,000 VND per hour.
