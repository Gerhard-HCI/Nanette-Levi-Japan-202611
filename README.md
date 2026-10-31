# Nanette-Levi-Japan-202611

Happy Camper travel companion for the Lopez-Lima Levi / Guzman Japan trip, 4–19 November 2026.
Live at https://nanette-levi.happycamper.food (GitHub Pages, deploys on every push to `main`).

The site is one file, `index.html`. Trip content comes from the HCI Canvas Google Sheet
(CANVAS tab for the programme, Confirmation tab for the statement). The Statement tab is
encrypted (AES-GCM-256, PBKDF2-SHA256, 250,000 iterations) with separate guest and staff codes.

## Change log

### 31 Oct 2026
- K8XHDFTW-0003 (Nanette Levi, USD 8,150) paid via Stripe (payout 29 Oct); marked paid on the statement and her Pay button removed. Outstanding: E7RB1XGD-0002 (Pauline Guzman, USD 3,975).

### 27 Oct 2026
- Balance invoices issued 26 Oct, one per couple: K8XHDFTW-0003 to Nanette Levi (USD 8,150 + 326 card fee = 8,476)
  and E7RB1XGD-0002 to Pauline Guzman (USD 3,975 + 159 card fee = 4,134). Both shown on the statement as unpaid.
- Paid arrangement fee now shown as two payments, K8XHDFTW-0001 (Lopez-Lima Levi) and E7RB1XGD-0001 (Guzman), 2,250 each.
- Statement shows one Stripe Pay button per couple (new `payLink`, `invoice`, `payAmount`, `payNote` on each split party).
- Guest and staff views both re-encrypted with the new figures.

### 26 Oct 2026
- Raimundo's movements per Traveledge (John Barone, 11 Sep): Kyoto → Tokyo on the evening of 16 Nov with a Tokyo hotel night, then JL045 Haneda 08:20 → Paris on 17 Nov.
- Sugalabo (5 Nov) back to 4 guests at the Tier 2 rate for four (USD 1,100); split stays 50/50.

### 24 Oct 2026 (later)
- Sugalabo (5 Nov) is now 2 guests, Nanette and Pauline, while Raimundo and Alberto are at their conference;
  fee reduced to the Tier 2 rate for two (USD 800) on the Canvas, Confirmation tab, itinerary, Wish List and statement.
- New "Cost split" tab in the Canvas workbook and a "Proposed split between the two couples" section on the
  Statement tab: shared items 50/50 (as with the arrangement fee), items after the Guzmans leave on 13 Nov
  charged to Nanette and Raimundo.

### 24 Oct 2026
- 15 Nov: private tea ceremony at Kanjoan added, 15:00, 2 guests, confirmed.
- Statement updated with the tea ceremony (USD 1,975 for 2, per the Happy Camper pricing guide of 23 Oct 2026).
- Confirmation tab corrected: Sugalabo on 5 Nov and Sushi Nakano on 6 Nov, matching the Canvas.

### 23 Oct 2026
- Kanjoan tea ceremony (12 Nov) removed; statement updated.

### 22 Oct 2026
- Sugalabo confirmed for 5 Nov 20:30; Sushi Nakano moved to 6 Nov 20:30.
- Statement repriced from the Confirmation tab.
- Expanded descriptions for all ten restaurants (chef, style, setting, signature dishes).
- Sushi Nakano identified as 仲野, 3-4-12 Minami-Aoyama; Motoyoshi's location corrected to Ebisu-nishi.

### 20 Oct 2026
- Sugalabo dropped from 6 Nov; dinner back to curate.

### 19 Oct 2026
- Statement rebuilt from the Confirmation tab. The Stripe link for the paid invoice was removed,
  so no Pay button shows until a new invoice link is added.

### 16 Oct 2026
- Nine dinners marked confirmed per the Canvas (Sushi Nakano, Tori Yamamoto, Imoto, Cenci, Oka,
  Matsu lunch, Miyoshi, Motoyoshi, Mitaka); Grand Sumo confirmed; geisha house experience
  confirmed for 21:00 on 11 Nov.
- Google Maps links added for restaurants and activities.

### 13 Oct 2026
- Tokyo hotel corrected to Palace Hotel Tokyo; dining programme aligned to the Canvas; FX converter set to 158.
