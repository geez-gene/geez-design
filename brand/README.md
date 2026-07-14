# Geez Design System — `/brand/`

The source of truth for the Geez brand. Session-independent. Shareable with any designer or agent.

> **This repo is public.** Two pieces of the system are deliberately **not here** — see *What's held privately*. Nothing is duplicated across the two: one section, one home. If a rule seems missing, it is held privately on purpose; ask Gene rather than reconstructing it.

---

## What's in here

| File | Authority for | Format |
|---|---|---|
| **`geez-design-tokens.json`** | **Machine** — colors, motion, spacing, precise design tokens. | W3C DTCG JSON |
| **`GZ-CONFORMANCE-001.md`** | **Law** — every design rule an agent must obey. | Markdown |
| `README.md` | This index. | Markdown |

**Rule of thumb:** need a *value* → JSON. Need to know the *rule* → conformance doc.

---

## What's held privately (and why)

In the private `geez-gene/geez` repo, under `brand-private/`:

| Held privately | Why |
|---|---|
| **`GZ-CONFORMANCE-001-CONSTITUTIONAL.md`** — GZ-OS-001 (the 1-2-3 OS) and the logo-change unlock phrase | Protected as **trade secret + copyright**. Publishing it in a public repo forfeits that protection — irreversibly. |
| **`geez-brand-repository.html`** — the visual reference (logos, type specimens, swatches, motion demos) | It embeds the **Spoof** faces as base64. Spoof is a commercial typeface from **[ABC Dinamo](https://abcdinamo.com)** and **the license is not yet signed**. Shipping the file here would redistribute the fonts. It moves into this repo once the license permits. |

Need either one? Ask Gene. **Do not restate them into this repo.**

---

## Sharing with Claude Design

Attach or point it at:

1. `geez-design-tokens.json` — exact colors, motion, and tokens to pull values from.
2. `GZ-CONFORMANCE-001.md` — the guardrails it must design within.
3. *(Gene only)* `geez-brand-repository.html` from the private repo — the visual reference. Without it, an agent has the rules and the values but has **not seen** the brand; for anything logo- or type-critical, get it from Gene rather than inventing.

One sentence to open the session:

> *"Design within the Geez system. Exact values: geez-design-tokens.json. Rules you cannot break: GZ-CONFORMANCE-001.md. Four colors only, Spoof font only, no scroll, 936ms heartbeat. If you have not seen the brand repository, do not invent the logo or the type — ask."*

---

## The non-negotiables (fast reference)

- **Four colors only** — `#AEFFC8` · `#DA0063` · `#000000` · `#FFFFFF`. **No variants.**
- **Spoof font only** — 6 weights, zero external deps. Never ship the raw font files (see licensing above).
- **No scroll** — every screen fits the viewport.
- **936ms heartbeat** — `cubic-bezier(0.16, 1, 0.3, 1)`.
- **Logo** — real asset only, never typed text. Changing it requires an exact confirmation phrase held privately.
- **Anonymity Seal** — architectural, non-configurable. No back doors.
- **Contrast Mark Law** — connective glyphs always carry the contrast color.
- **Precise tokens** — stroke 4.31px · radius 8.62px · pill stroke 1.751px (never rounded).
- **Three Rooms** — CALM · CONSISTENT · CONNECTED.

Full detail: `GZ-CONFORMANCE-001.md`.

---

## Versioning

- Tokens: **v3.0** · Conformance: **v1.0** — current as of this package.
- Brand Repository HTML: **v2.0** (assets locked May 19, 2026), held privately → **flagged for v3.0** fold-in of the June laws.

When any file changes, bump its version header and note it here.

---

*Geez LLC · Delaware · geez.network · Launch October 18, 2026*
