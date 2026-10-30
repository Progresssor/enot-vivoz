# Design

World: a dark green night showroom. Soft light falls from above, out-of-focus foliage frames the edges, and containers stand as exhibits on round podiums. The raccoon mascot sits under a glass dome. The style follows a reference the owner supplied (a premium plant-shop layout).

## Color
- Ground #07150D → #0B1F14 with radial green light pools
- Cards #143221 → #10291B, hairlines rgba(170,230,150,.12)
- Ink #EEF5EA, secondary #A9BCA6, headline mint #B9E8A0
- Brand green #8BE22B (primary buttons as a #9BEA45→#6FC21C gradient, dots, selected states)

## Type
- Manrope: headlines at 600, second line of a heading at 300 in ink color
- Golos Text: body and UI

## Imagery
- hero-container.webp: owner's real container photo, background removed, phone repainted to 8 967 155-03-03
- c8/c20/c27.webp: 3D renders (three.js) in brand livery on podiums. Illustrative, not photos.
- Foliage: inline SVG leaves at three blur depths

## Components
Rounded 28px cards, 14px buttons, pill chips for options, glass dome with highlight strips, CSS podium (ellipse top plus dark rim). On phones, a floating dock with Call / WhatsApp / Max.

## Motion
The hero container rises softly on load. Cards lift on hover.
