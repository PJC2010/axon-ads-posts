# Axon — "One Clear Picture" motion design ad

Generated with the `06-motion-design-ad` (Seedance 2.0 on Higgsfield) skill, restyled to Axon's
actual brand system instead of the skill's generic dark/neon defaults. Render model switched to
`kling3_0` — see "Notes on generating this" below.

**Product**: Axon — an enterprise-grade business-intelligence dashboard built for small businesses
that don't have a data team. It pulls sales, ops, and finance data out of scattered spreadsheets
and receipts into one calm, readable dashboard.
**Audience**: small business owners — not analysts. They want clarity, not more software to learn.
**Category**: SaaS Dashboard (BI/analytics)
**Format**: 30s, 16:9 (1920×1080), 30fps — landscape for web/YouTube/LinkedIn.
A 9:16 cut (1080×1920, same beats, tighter crops) is noted at the bottom for Reels/TikTok/Stories.

---

## Visual style: "Warm Editorial / Calm Data"

The skill's built-in style library (Dark Premium, Neon Cyber, Abstract Data, etc.) is written for
cold, high-contrast tech brands. Axon is the opposite on purpose — a trusted advisor, not a
trading terminal — so this ad uses Axon's real design tokens instead:

- **Canvas**: warm paper (`#F7F4EE`), never pure white or black
- **Text/ink**: near-black ink (`#16181D`), never pure black
- **Signature accent**: deep ocean (`#1A5A75`) — used once or twice per beat, never as a wash
- **Data palette**: desaturated moss, gold, plum, and dusty rose for chart series — muted, never neon
- **Shape language**: 1px hairline borders, soft warm drop shadows, 10px card radius, 6px button radius
- **Type**: Roboto Slab for the big display line, Geist for supporting copy, Geist Mono for any numeral/metric
- **Motion**: restrained — three easings only (ease-out for entrances, ease-in-out for holds,
  linear for counters), **no bounce, no elastic overshoot, no glow/bloom**
- **Iconography**: Lucide-style line icons, 1.5px stroke, no emoji, no filled icons
- **Voice**: sentence case only, no emoji, em dashes welcome. Confident and quiet, not hyped.

---

## Narrative flow

### [OPENING HOOK — 0:00–0:02] — Glitch-to-Clean, reskinned warm
A cluttered warm-paper desktop: overlapping spreadsheet cells, a curled paper receipt, a sticky
note, a half-cropped screenshot — all in slightly different, clashing colors, jittering and
overlapping like an anxious desk. Ink-colored numbers flicker illegibly across them.
In one clean 0.6s motion (ease-in-out, no glitch/pixelation artifacts — this is a *tidy* snap,
not a digital malfunction) everything **collapses and reassembles** into a single flat card on
warm paper: a hairline-bordered Axon dashboard tile with a soft warm drop shadow.
**Sound**: a soft paper-shuffle whoosh resolving into one gentle, low chime — no bass drop, no synth stab.

### [PRODUCT SHOWCASE — 0:02–0:14]
The single dashboard card scales up gently (ease-out, 0:02–0:03) to fill the frame, revealing the
full Axon interface on its warm paper canvas: a left sidebar, a top bar, and a grid of metric and
chart cards, exactly as in the product's real UI kit (`Sidebar`, `TopBar`, `MetricCard`, `ChartCard`).
Four elements highlight in sequence, each a simple fade + 4px rise (0.5s, ease-out), no morphing
or particle effects:

1. **Revenue MetricCard** (0:02.5–0:04.5): a large Geist Mono number counts up quietly from 0 to
   this week's revenue figure, deep ocean accent underline, moss-green "+12%" trend tag beside it
2. **Weekly trend ChartCard** (0:04.5–0:07): a restrained line chart draws itself left-to-right in
   deep ocean, no glow — just a clean stroke animating along its path
3. **Connections view** (0:07–0:10): three small integration tiles (bank, POS, invoicing) fade in
   with a single hairline connecting line each, moss/gold/plum accent dots marking each source
4. **Digest summary** (0:10–0:14): a plain-language one-line insight types in at natural reading
   speed — *"Revenue is up 12% this week, driven mostly by weekend orders."* — Roboto Slab, ink on paper

Camera stays static and centered throughout; the only motion is inside the UI. No isometric tilt,
no 3D rotation — Axon's interface should read as a real, still, trustworthy surface.
**Sound**: near-silent under this beat — one soft "tick" per element as it settles, -18dB, and a
single quiet counter-tick sequence under the revenue number.

### [BENEFIT COMMUNICATION — 0:14–0:23]
The dashboard fades to 55% opacity and holds. A single display line sets in Roboto Slab, ink,
fading and rising 4px into place (0.8s, ease-out), centered:

**"One clear picture of your business."**

Below it, three short benefit lines enter one at a time with a 0.5s stagger (fade + 4px rise,
no slide-from-side, no icons bouncing):

- "Every number, in one place — sentence case, no jargon"
- "Real answers, not more charts to interpret"
- "No analyst required"

Each line's leading word is set once in deep ocean for emphasis; everything else stays ink.
**Sound**: silence, then one very soft chime as the display line lands — nothing under the three
supporting lines.

### [CALL-TO-ACTION — 0:23–0:28]
Dashboard returns to full opacity, still static and calm. The Axon mark (`mark.svg`, never
redrawn) fades in top-left, small and quiet. Centered below the dashboard, a single button
appears — 6px radius, deep ocean fill, warm paper text, soft warm shadow:

**"Try Axon free"**

The button does one restrained thing only: a 3% scale breathe, ease-in-out, once — no pulsing
loop, no glow ring. Small supporting line beneath in Geist, muted ink: "No credit card required."
**Sound**: the same low chime from the opening hook returns, closing the loop — nothing louder.

### [HOLD — 0:28–0:30]
Everything settles; last frame holds on the dashboard, mark, and button at full opacity for the
final 2 seconds so the CTA is legible on a paused frame or thumbnail.

---

## Technical specs (for Seedance 2.0 on Higgsfield)

```
Duration: 30 seconds
Aspect Ratio: 16:9 (1920x1080)
Frame Rate: 30fps
Style Tone: Warm Editorial / Calm Data (custom — not Dark Premium, not Neon Cyber)
Color Grading: warm neutral daylight, low contrast, no crushed blacks, no cyan/teal color cast
Palette: canvas #F7F4EE, ink #16181D, accent #1A5A75 (deep ocean), data accents desaturated
  moss / gold / plum / dusty rose — used sparingly, one accent per element
Camera: static, centered, no zoom/orbit/isometric tilt — the UI is the only thing that moves
Motion Easing: ease-out for entrances, ease-in-out for holds, linear for numeric counters —
  no elastic, no bounce, no overshoot
Typography: Roboto Slab for the display line, Geist for supporting copy, Geist Mono for numerals
Shape Language: 1px hairline borders, soft warm drop shadows, 10px card radius, 6px button radius
Iconography: line icons only, 1.5px stroke, no emoji, no filled icons
Sound Design: paper-shuffle whoosh -> single soft chime (open), quiet settle-ticks (showcase),
  near-silence under benefit copy, one closing chime under the CTA — overall mix stays under
  -12dB, no bass drops, no synth stabs
Mood & Energy: quiet confidence — a trusted advisor, not a hype reel
Target Emotion: relief and clarity, not urgency
Pacing: deliberate — one idea on screen at a time, 2-4 second beats, plenty of paper-colored
  negative space
```

## 9:16 cut (Reels / TikTok / Stories, 15s)

Same four beats compressed: hook (0–1.5s), showcase — revenue card + one chart only (1.5–7s),
single benefit line only, "One clear picture of your business." (7–11s), CTA (11–15s). Crop the
dashboard to a single vertical stack of cards rather than the full multi-column grid; keep the
mark and button centered in the safe zone (middle 60% of frame).

---

## Notes on generating this

- Higgsfield model: `kling3_0` (switched from the skill's default `seedance_2_5` — see below).
- Generations are capped well under 30s per call — render this as shorter clips along the beat
  boundaries above and stitch, rather than one 30s call.
- **Cost check (this session)**: at current pricing a single 6-second `kling3_0` clip at 16:9 is
  ~12 credits, and a 10-second clip is ~20 credits — much cheaper than `seedance_2_5` (~39 / ~65
  credits for the same durations). The connected Higgsfield account currently holds
  **32.11 credits**, enough for one 10s clip plus a 6s clip, or two 6s clips with credits to
  spare. Still short of the 4-5 clips a full 30s render needs — top up for the complete ad, or
  render the opening hook + CTA beats first as a proof of concept.
- `kling3_0` is Higgsfield's pick for multi-shot, audio, or motion-transfer generations (per the
  `generate_video` tool defaults) rather than Seedance's single-shot text-to-video strength — the
  beat-by-beat script above should still translate directly since each beat is scripted as its
  own short shot already.
