# Design

World: a construction site at night, told through the materials of the job. Steel of the branded containers and stencil numerals painted on metal. Restraint reads as expensive: no glows, one action colour. Chosen by the owner on 2026-11-09 ("Тёмный строже").

## Color
- Ground #0A0C0A, raised panels #121512, hairlines rgba(255,255,255,.08), steel #2A302A
- Ink #F4F6F1, secondary #A9B0A5
- Green #8BE22B — actions only (primary buttons, selected chips, dock call). Text on green #0B1F06
- Yellow #FFD21F — brand signature, used sparingly: «ЗАБЕРЁТ» lettering, slogan emphasis, «Берут чаще» tag, list markers, promise icons
- No radial glows, no gradient buttons, no coloured halos

## Type
- Unbounded 500: headings, uppercase, tight tracking; Unbounded 800 only for stencil numerals 8 / 20 / 27 and the logo
- Golos Text: body and UI
- Pangolin: only the hand-lettered «ЗАБЕРЁТ»

## Motifs
- Dividers are thin 1px hairlines. The owner rejected the reflective-tape stripes (2026-11-09): do not bring them back
- Stencil numerals: a thin horizontal bridge cut through the container volumes
- Containers stand in one line at true relative scale (3.6 / 6.0 / 6.0 m) on a shared ground line; on phones a compact list

## Imagery
- zbox8/20/27.webp: owner's real branded containers, background removed
- ztruck.webp: liveried truck «Сервис Енот Заберёт»
- Raccoon mascots, all 3D, only two on the page (owner removed enot-bag and enot-phone 2026-11-09; rejects the flat drawn enot.webp): enot3d (hero), logo-enot with crossed arms (final)

## Components
14px buttons, flat green primary, outlined secondary, press scale .97 on tap. Panels 20px radius. The order message reads as a receipt (dashed rules, no nested card); result panel is sticky on desktop. On phones a fixed dock: Call / WhatsApp / Max.

## Motion
Hero text rises once on load (0.7 s, staggered). The slogan is its own screen: words light from grey to ink as it scrolls into view, «Енот заберёт!» ends yellow. Second authored moment: the truck drives in, brakes, idles for ~3 s and settles. Mascots appear once and rest. Toast for Max copy slides up 200 ms ease-out. Everything off under prefers-reduced-motion.
