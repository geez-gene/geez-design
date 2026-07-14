# GZ-CONFORMANCE-001 — Geez Design & Constitutional Conformance

> **Version 1.0 · Locked**
> The single home for every Geez law an agent, designer, or engineer must obey.
> Values live in `geez-design-tokens.json`. Assets live in `geez-brand-repository.html` — **held in the private `geez` repo**, not here (it embeds licensed font binaries; see §2 Spoof).
> **Laws live here.** If a decision conflicts with this document, this document wins.

---

## 0. How to read this

Three tiers of rule:

- **Constitutional** — architectural and legal. Cannot be toggled, configured, or overridden in product. Reopening requires an explicit founder unlock.
- **Design Law** — governs every surface, artifact, and screen. Violations are flagged, never silently committed.
- **Standard** — the house style. Applied by default.

---

## 1. Constitutional Doctrines

> **This repository is public.** Doctrines that are protected as trade secret are **not published here** — they live in the private law-of-record, `brand-private/GZ-CONFORMANCE-001-CONSTITUTIONAL.md` in the private `geez-gene/geez` repo. They are not restated in this file, and this file must never be edited to restate them. One section, one home.

### GZ-OS-001 — The 1-2-3 OS
- **Held privately. Trade secret + copyright.** See the private law-of-record.
- Binding on every Geez surface even though it is not printed here. If you are designing or building against the OS and cannot read it, **stop and ask Gene** — do not infer it.
- The one rule safe to state publicly: Geez is a **coordination layer only** — never fulfillment, payment, or data ownership.

### Anonymity Seal
- **Architectural and non-configurable.** Unconditional. There is no setting to turn it off.
- **No Back Doors corollary:** no master keys, no employee override, no undisclosed telemetry.

### GZ-COMMS-001 — Communication Minimalism
- The system says less. Every added word, field, or step must justify itself against silence.

### GZ-ACCESS-001 — Universal Access
- **Default-on, not toggle-on.** Accessibility is the baseline state, not an opt-in.

---

## 2. Design Law

### Logo
- **Always the real PNG/SVG asset, base64-embedded.** Never typed text, never a CSS/wordmark recreation.
- If the asset is not in-session, **stop and ask Gene to upload** before building.
- Changing the logo requires Gene to type an **exact confirmation phrase**, held in the private law-of-record. Nothing less unlocks it. If you do not know the phrase, you are not the person who unlocks the logo.

### Four Colors Only
- `#AEFFC8` Green · `#DA0063` Magenta · `#000000` Black · `#FFFFFF` White.
- No new colors. No gray scale. Depth comes from the four colors + opacity.
- Green is **light** — never white/light text on it. Magenta is **dark** — white text on it.

### Spoof Font Only
- Six weights, base64 woff2, **zero external font dependencies.**
- **Licensing (open, 2026-07-14).** Spoof is a commercial typeface from **[ABC Dinamo](https://abcdinamo.com)**. Per `geez-network/docs/market-research/brand-strategy.html`, **the license is not yet signed.** Until it is: the font binaries and the base64-embedded `geez-brand-repository.html` **stay out of this public repo** — publishing them redistributes the faces. Public Geez surfaces load Spoof from a Geez-controlled domain; they never ship the raw files. Do not add font binaries here.
- Extraction note (private copy): match `data:font/truetype` MIME type (a woff2 query returns zero results even though the fonts are present).

### No Scroll
- **Every screen fits the viewport.** Absolute.
- If content doesn't fit, it is **flagged as a design violation** — scroll is never added silently.

### 936ms Heartbeat
- All screen transitions run at **936ms** on **cubic-bezier(0.16, 1, 0.3, 1).** Non-negotiable.

### Contrast Mark Law *(June 6, 2026)*
- Connective glyphs — `•  ·  |  /  =  →  –  —  +  ~  '  &` — **always carry the contrast color:**
  - **magenta** when set against dark text
  - **black** when set on a magenta field
- A glyph **never** takes the words' own color.

### Precise Design Tokens
- Stroke **4.31px** · Radius **8.62px** · Pill stroke **1.751px**.
- Pill stroke is **exact** — never rounded to 2px. **Rounding = violation.**

---

## 3. Standard — House Style

### Atelier Artifact Standard
- White background · **6px Geez Green top border** · 64px padding · **Spoof Light 300** body · magenta for priority callouts.
- Every asset **self-contained, base64-embedded, zero external dependencies.**

### The Three Rooms
- **CALM · CONSISTENT · CONNECTED.** This *is* Geez.
- "Luxury / Trust / Method" is a prior error — **never use it.**

---

## 4. Precedence

Constitutional > Design Law > Standard.
When any two conflict, the higher tier governs. When in doubt, **choose the more minimal, more anonymous, more accessible** option — that is always the Geez-aligned direction.

---

*Geez LLC · Delaware · geez.network · Launch October 18, 2026*
