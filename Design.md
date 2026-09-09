---
version: alpha
name: LG-EI-design-foundation
description: "A red-accented, two-layer design-token system (Primitive to Semantic) for LG Electronics' Web/EI properties. A single primary accent, Active Red (#EA1917), carries every primary action across a strict 4px-multiple spacing/layout ladder and a six-step radius scale mapped explicitly to component categories (Badge/Chip to Button small/medium/large to Card to Pill/Toast). Typography runs a dual-typeface system: LGEIHeadline (semibold-only, for titles) paired with LGEIText (regular/semibold, for everything else), with every text style annotated against a WSG (Web Style Guide) usage citation rather than left as a free-standing number. There is no elevation/shadow scale and no page-level dark-mode alternation; this is a governance-first token sheet, not a rendered UI."

colors:
  # --- Primitives: Primary ---
  active-red: "#ea1917"
  black: "#000000"
  white: "#ffffff"
  logo-gray: "#6b6b6b"
  white-60: "rgba(255,255,255,0.6)"
  # --- Primitives: Gray Scale ---
  light-gray-0: "#f6f6f6"
  light-gray-1: "#f6f3eb"
  light-gray-2: "#f0ece4"
  light-gray-3: "#e6e1d6"
  mid-gray-1: "#cbc8c2"
  mid-gray-2: "#646464"
  mid-gray-3: "#4a4946"
  dark-gray-1: "#333333"
  dark-gray-2: "#262626"
  dark-gray-3: "#1a1a1a"
  # --- Primitives: Functional / State ---
  heritage-red: "#a50034"
  green-1: "#287d00"
  green-2: "#316d15"
  yellow-1: "#f7b500"
  yellow-2: "#eeb404"
  teal-1: "#006a63"
  toast-gray: "#303030"
  bright-red: "#ff3224"
  ad-red: "#fd312e"
  near-black: "#141414"
  # --- Semantic: Background ---
  bg/default: "#ffffff"
  bg/warm: "#f0ece4"
  bg/subtle: "#f6f3eb"
  bg/elevated: "#ffffff"
  bg/light: "#f6f6f6"
  # --- Semantic: Surface ---
  surface/card: "#ffffff"
  surface/toast-error: "#303030"
  surface/toast-warning: "#eeb404"
  surface/toast-info: "#006a63"
  surface/inverse: "#333333"
  surface/blur-blind: "rgba(255,255,255,0.6)"
  # --- Semantic: Text ---
  text/primary: "#000000"
  text/secondary: "#333333"
  text/tertiary: "#646464"
  text/disabled: "#cbc8c2"
  text/inverse: "#ffffff"
  text/brand: "#ea1917"
  text/disclaimer: "#000000"
  text/disclaimer-inverse: "#ffffff"
  text/on-toast-error: "#ffffff"
  text/on-toast-warning: "#000000"
  text/on-toast-info: "#ffffff"
  # --- Semantic: Border, Brand & Status ---
  border/default: "#e6e1d6"
  border/strong: "#cbc8c2"
  border/focus: "#000000"
  border/inverse: "#ffffff"
  brand/primary: "#ea1917"
  brand/logo: "#a50034"
  brand/logo-inverse: "#ffffff"
  brand/secondary: "#6b6b6b"
  state/success: "#287d00"
  state/success-on-warm: "#316d15"
  state/warning: "#eeb404"
  state/error: "#ea1917"
  state/error-on-warm: "#a50034"
  state/info: "#006a63"
  review/star: "#ea1917"
  # --- Semantic: Icon ---
  icon/default: "#000000"
  icon/active: "#ea1917"
  icon/muted: "#646464"
  icon/white: "#ffffff"
  flag/general: "#000000"
  flag/promotion: "#ea1917"
  # --- Semantic: Action ---
  action/primary: "#ea1917"
  action/promo: "#fd312e"
  action/primary-label: "#ffffff"
  action/secondary: "#ffffff"
  action/secondary-label: "#000000"
  action/secondary-border: "#646464"
  action/disabled: "#cbc8c2"
  # --- Semantic: Shadow (text-halo, not elevation) ---
  shadow/disclaimer: "#ffffff"
  shadow/disclaimer-inverse: "#000000"
  # --- Decorative: the system's only gradient ---
  badge-gradient: "linear-gradient(to right, #ff3224 0%, #ea1917 50%, #a50034 100%)"

typography:
  font-family/headline: "LGEIHeadline"
  font-family/text: "LGEIText"
  font-size/12: 12px
  font-size/14: 14px
  font-size/16: 16px
  font-size/20: 20px
  font-size/24: 24px
  font-size/32: 32px
  font-size/36: 36px
  font-size/56: 56px
  font-size/60: 60px
  font-size/80: 80px
  font-weight/regular: 400
  font-weight/semibold: 600
  title/xlarge:
    fontFamily: "LGEIHeadline, Noto Sans KR, system-ui, sans-serif"
    fontSize: 80px
    fontWeight: 600
    lineHeight: 80px
    letterSpacing: 0
  title/large:
    fontFamily: "LGEIHeadline, Noto Sans KR, system-ui, sans-serif"
    fontSize: 60px
    fontWeight: 600
    lineHeight: 60px
    letterSpacing: 0
  title/medium:
    fontFamily: "LGEIHeadline, Noto Sans KR, system-ui, sans-serif"
    fontSize: 56px
    fontWeight: 600
    lineHeight: 60px
    letterSpacing: 0
  title/small:
    fontFamily: "LGEIHeadline, Noto Sans KR, system-ui, sans-serif"
    fontSize: 32px
    fontWeight: 600
    lineHeight: 36px
    letterSpacing: 0
  subtitle/large:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 42px
    letterSpacing: 0
  subtitle/medium:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0
  subtitle/medium-strong:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 28px
    letterSpacing: 0
  body/default:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0
  body/default-strong:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0
  cta/medium:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0
  nav/menu:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0
  badge/small:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 14px
    letterSpacing: 0
  body/small:
    fontFamily: "LGEIText, Noto Sans KR, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 16px
    letterSpacing: 0

rounded:
  radius/4: 4px
  radius/6: 6px
  radius/8: 8px
  radius/12: 12px
  radius/28: 28px
  radius/full: 9999px

spacing:
  spacing/4: 4px
  spacing/8: 8px
  spacing/12: 12px
  spacing/16: 16px
  spacing/20: 20px
  spacing/24: 24px
  spacing/32: 32px
  spacing/40: 40px
  spacing/48: 48px
  spacing/64: 64px

layout:
  layout/viewport: 1920px
  layout/banner: 1600px
  layout/container: 1440px
  layout/gutter: 24px
  layout/viewport-inset: 240px
  layout/banner-inset: 160px
  layout/banner-padding: 80px
  layout/filter-width: 240px

components:
  button-box-primary:
    backgroundColor: "{colors.action/primary}"
    textColor: "{colors.action/primary-label}"
    typography: "{typography.cta/medium}"
    rounded: "{rounded.radius/full}"
  button-box-promo:
    backgroundColor: "{colors.action/promo}"
    textColor: "{colors.action/primary-label}"
    typography: "{typography.cta/medium}"
    rounded: "{rounded.radius/full}"
  button-box-secondary:
    backgroundColor: "{colors.action/secondary}"
    textColor: "{colors.action/secondary-label}"
    borderColor: "{colors.action/secondary-border}"
    typography: "{typography.cta/medium}"
    rounded: "{rounded.radius/full}"
  button-box-disabled:
    backgroundColor: "{colors.action/disabled}"
    textColor: "{colors.text/inverse}"
    rounded: "{rounded.radius/full}"
  button-contained-small:
    backgroundColor: "{colors.action/primary}"
    textColor: "{colors.action/primary-label}"
    rounded: "{rounded.radius/6}"
  button-contained-medium:
    backgroundColor: "{colors.action/primary}"
    textColor: "{colors.action/primary-label}"
    rounded: "{rounded.radius/8}"
  button-contained-large:
    backgroundColor: "{colors.action/primary}"
    textColor: "{colors.action/primary-label}"
    rounded: "{rounded.radius/12}"
  text-field:
    backgroundColor: "{colors.bg/default}"
    textColor: "{colors.text/primary}"
    borderColor: "{colors.border/default}"
    borderColorFocus: "{colors.border/focus}"
    borderColorError: "{colors.state/error}"
    borderColorErrorOnWarm: "{colors.state/error-on-warm}"
    borderColorSuccessOnWarm: "{colors.state/success-on-warm}"
    typography: "{typography.body/default}"
    rounded: "{rounded.radius/8}"
  badge-chip:
    typography: "{typography.badge/small}"
    rounded: "{rounded.radius/4}"
  badge-promotion:
    backgroundColor: "{colors.badge-gradient}"
    textColor: "{colors.text/inverse}"
    typography: "{typography.badge/small}"
    rounded: "{rounded.radius/4}"
  card:
    backgroundColor: "{colors.surface/card}"
    textColor: "{colors.text/primary}"
    rounded: "{rounded.radius/28}"
    margin: "{spacing.spacing/32}"
  toast-error:
    backgroundColor: "{colors.surface/toast-error}"
    textColor: "{colors.text/on-toast-error}"
    rounded: "{rounded.radius/full}"
  toast-warning:
    backgroundColor: "{colors.surface/toast-warning}"
    textColor: "{colors.text/on-toast-warning}"
    rounded: "{rounded.radius/full}"
  toast-info:
    backgroundColor: "{colors.surface/toast-info}"
    textColor: "{colors.text/on-toast-info}"
    rounded: "{rounded.radius/full}"
  gnb-promotion-bar:
    backgroundColor: "{colors.surface/inverse}"
    textColor: "{colors.text/inverse}"
    typography: "{typography.nav/menu}"
  blur-blind-overlay:
    backgroundColor: "{colors.surface/blur-blind}"
  banner:
    maxWidth: "{layout.layout/banner}"
    inset: "{layout.layout/banner-inset}"
    padding: "{layout.layout/banner-padding}"
  section-container:
    maxWidth: "{layout.layout/container}"
    viewport: "{layout.layout/viewport}"
    inset: "{layout.layout/viewport-inset}"
    gutter: "{layout.layout/gutter}"
  filter-panel:
    width: "{layout.layout/filter-width}"
  fine-print-disclaimer:
    textColor: "{colors.text/disclaimer}"
    haloColor: "{colors.shadow/disclaimer}"
  fine-print-disclaimer-inverse:
    textColor: "{colors.text/disclaimer-inverse}"
    haloColor: "{colors.shadow/disclaimer-inverse}"
---

## Overview

This file documents a **design-token foundation sheet** — four "spec" frames (Color, Typography, Spacing/Layout, Radius) built as a governance artifact, not a rendered product screen. Unlike a photography-first catalog, there is no hero imagery, no page chrome, and no component mockups here: every frame is a literal reference table — `Variable | Type | Value` for primitives, `Semantic Token ← Primitive Ref | HEX` for aliases, `Variable | px | 용도(usage) | Sample` for spacing/radius. The document's job is to be copy-pasted into implementation, not to look like a website.

The architecture is explicitly **two-layer**: raw **Primitive** values (`active-red`, `dark-gray-3`, `heritage-red` …) sit underneath **Semantic** aliases (`bg/default`, `text/primary`, `action/primary` …) that point back to exactly one primitive each — the sheet renders this as a literal `←` arrow between the semantic name and its primitive source, so the provenance of every color is traceable by eye. Nothing in the semantic layer is ever a "new" hex; it is always a pointer.

A single accent — **Active Red** `#EA1917` — plays the same role Apple's Action Blue plays: it is the only color used for `action/primary`, `text/brand`, `icon/active`, `border/brand/primary`, `flag/promotion`, and `review/star`. The one deliberate exception is `action/promo` (`ad-red` `#FD312E`), a near-identical red reserved specifically for advertising/promotional CTAs so analytics can distinguish commerce intent from ad intent without a visual difference a user would notice.

Typography is a **dual-typeface** system rather than Apple's single-family/two-optical-size approach: **LGEIHeadline** (semibold only) renders every `title/*` style, while **LGEIText** (regular or semibold) renders everything else — subtitles, body, CTA labels, nav, badges. There is no "medium" weight and no italic; the ladder is exactly two weights.

Spacing, layout widths, and radii all snap to a **4px-multiple grid**, and — distinctively — nearly every non-trivial token carries a **"WSG" (Web Style Guide) citation** explaining exactly which page pattern it was measured from (e.g. `spacing/32` — "WSG Card Common Principle — Card margin (Desktop)"). This turns the sheet into an audit trail: a designer or engineer can trace any spacing decision back to the specific layout rule that produced it.

**Key Characteristics:**
- Primitive → Semantic two-layer color architecture with a visible `←` provenance arrow on every semantic row.
- One primary accent (`{colors.action/primary}` — Active Red #EA1917) plus a near-identical, deliberately separate promo accent (`{colors.action/promo}` — #FD312E) for ad/commerce disambiguation.
- Dual-typeface hierarchy: LGEIHeadline (semibold-only, titles) vs. LGEIText (regular/semibold, everything else) — a hard boundary, no mixing.
- Exactly two font weights exist as tokens (400 / 600) — no "medium," no "bold" token, no italics.
- Six-step radius scale where every step names its component target directly (Badge/Chip → Button small → Button medium → Button large → Card → Pill/Toast) rather than using abstract size names.
- 4px-multiple spacing AND layout grid, each token annotated with a "WSG" usage citation rather than left as a bare number.
- `-on-warm` state-color variants (`state/success-on-warm`, `state/error-on-warm`) exist specifically because the standard state colors lose contrast on the `{colors.bg/warm}` surface — a subtlety with no Apple-side equivalent.
- Exactly one gradient in the whole system (`{colors.badge-gradient}`), reserved for promotional badges, and explicitly documented as *not* variable-bound (raw hex stops only).
- No elevation/shadow scale and no page-level dark-mode tile alternation — the only "shadow" tokens are text-halo colors for legal disclaimers over photography.

## Colors

> **Source analyzed:** the "tokens" foundation section of the file (node `19561:25592`), specifically its four sub-frames: *Color Design System Guide*, *Typography Design System Guide*, *Spacing Design System Guide*, and *Radius Design System Guide*. This is a token-definition sheet, not applied product screens — every color below is cited from its own reference table, not inferred from a mockup.

### Primitives

**Primary**
- **Active Red** (`active-red` — #EA1917): The one brand/action primitive. Everything that reads as "click me" or "this is LG red" traces back here.
- **Black** (`black` — #000000) / **White** (`white` — #FFFFFF): The two absolute poles; almost every semantic default resolves to one of these two.
- **Logo Gray** (`logo-gray` — #6B6B6B): Secondary brand neutral, used for the secondary-button border.
- **White 60** (`white-60` — rgba(255,255,255,0.6)): A translucent white used only for the blur/blind overlay surface.

**Gray Scale** (10 steps, light → dark)
- **Light**: `light-gray-0` #F6F6F6 · `light-gray-1` #F6F3EB · `light-gray-2` #F0ECE4 · `light-gray-3` #E6E1D6 — four near-white steps, each just warm/cool enough to create rhythm the way Apple's Parchment does against pure white.
- **Mid**: `mid-gray-1` #CBC8C2 · `mid-gray-2` #646464 · `mid-gray-3` #4A4946 — disabled states, secondary text, muted icons.
- **Dark**: `dark-gray-1` #333333 · `dark-gray-2` #262626 · `dark-gray-3` #1A1A1A — secondary text and the one inverse surface (`surface/inverse`).

**Functional / State**
- **Heritage Red** (`heritage-red` — #A50034): The LG *logo* color on light backgrounds — distinct from Active Red, reserved for brand-mark fidelity and the "error on warm" state.
- **Green 1/2** (#287D00 / #316D15), **Yellow 1/2** (#F7B500 / #EEB404), **Teal 1** (#006A63): success / warning / info primitives — Teal, not blue, carries "info," a deliberate departure from the blue-for-info convention seen in most Western systems (and in the Apple sheet's own link-blue).
- **Toast Gray** (#303030), **Bright Red** (#FF3224), **Ad Red** (#FD312E), **Near Black** (#141414): toast/overlay-specific neutrals and reds, kept distinct from the gray-scale and primary-red ladders so toast/ad surfaces can evolve independently.

**Badge Gradient** — `#FF3224 → #EA1917 → #A50034`, left to right. The system's *only* gradient, and explicitly called out in the source as not variable-bound ("그라디언트 스톱 변수 바인딩 미지원 — raw hex" / "gradient stop variable binding unsupported — raw hex"). Treat it as a fixed brand asset, not a themeable token.

### Semantic Tokens

Every row below follows the pattern `semantic-token ← primitive-name` exactly as the source table renders it.

**Background**
| Token | ← Primitive | Hex |
|---|---|---|
| `bg/default` | white | #FFFFFF |
| `bg/warm` | light-gray-2 | #F0ECE4 |
| `bg/subtle` | light-gray-1 | #F6F3EB |
| `bg/elevated` | white | #FFFFFF |
| `bg/light` | light-gray-0 | #F6F6F6 |

**Surface**
| Token | ← Primitive | Hex / Note |
|---|---|---|
| `surface/card` | white | #FFFFFF |
| `surface/toast-error` | toast-gray | #303030 |
| `surface/toast-warning` | yellow-2 | #EEB404 |
| `surface/toast-info` | teal-1 | #006A63 |
| `surface/inverse` | dark-gray-1 | #333333 — "GNB 프로모션 바 등 어두운 배경" (GNB promotion bar and other dark backgrounds) |
| `surface/blur-blind` | white-60 | #FFFFFF @ 60% |

**Text**
| Token | ← Primitive | Hex / Note |
|---|---|---|
| `text/primary` | black | #000000 |
| `text/secondary` | dark-gray-1 | #333333 |
| `text/tertiary` | mid-gray-2 | #646464 |
| `text/disabled` | mid-gray-1 | #CBC8C2 |
| `text/inverse` | white | #FFFFFF — text on dark images/backgrounds |
| `text/brand` | active-red | #EA1917 |
| `text/disclaimer` | black | #000000 — fine-print on light backgrounds |
| `text/disclaimer-inverse` | white | #FFFFFF — fine-print on dark backgrounds |
| `text/on-toast-error` | white | #FFFFFF |
| `text/on-toast-warning` | black | #000000 |
| `text/on-toast-info` | white | #FFFFFF |

**Border, Brand & Status**
| Token | ← Primitive | Hex / Note |
|---|---|---|
| `border/default` | light-gray-3 | #E6E1D6 |
| `border/strong` | mid-gray-1 | #CBC8C2 |
| `border/focus` | black | #000000 |
| `border/inverse` | white | #FFFFFF |
| `brand/primary` | active-red | #EA1917 |
| `brand/logo` | heritage-red | #A50034 — LG logo default color (light bg) |
| `brand/logo-inverse` | white | #FFFFFF — logo on dark bg |
| `brand/secondary` | logo-gray | #6B6B6B |
| `state/success` | green-1 | #287D00 |
| `state/success-on-warm` | green-2 | #316D15 — valid input specifically on `bg/warm` |
| `state/warning` | yellow-2 | #EEB404 |
| `state/error` | active-red | #EA1917 |
| `state/error-on-warm` | heritage-red | #A50034 — input error specifically on `bg/warm` |
| `state/info` | teal-1 | #006A63 |
| `review/star` | active-red | #EA1917 |

**Icon**
| Token | ← Primitive | Hex / Note |
|---|---|---|
| `icon/default` | black | #000000 |
| `icon/active` | active-red | #EA1917 |
| `icon/muted` | mid-gray-2 | #646464 |
| `icon/white` | white | #FFFFFF — icons over dark backgrounds |
| `flag/general` | black | #000000 |
| `flag/promotion` | active-red | #EA1917 |

**Action**
| Token | ← Primitive | Hex / Note |
|---|---|---|
| `action/primary` | active-red | #EA1917 — web CTA (e.g. "Buy Now") |
| `action/promo` | ad-red | #FD312E — advertising/promotional CTA |
| `action/primary-label` | white | #FFFFFF |
| `action/secondary` | white | #FFFFFF |
| `action/secondary-label` | black | #000000 |
| `action/secondary-border` | mid-gray-2 | #646464 |
| `action/disabled` | mid-gray-1 | #CBC8C2 |

**Shadow** (text-halo, not elevation)
| Token | ← Primitive | Hex / Note |
|---|---|---|
| `shadow/disclaimer` | white | #FFFFFF — contrast halo behind black text on light backgrounds |
| `shadow/disclaimer-inverse` | black | #000000 — contrast halo behind white text on dark backgrounds |

## Typography

### Font Family
- **Headline**: `font-family/headline` → `"LGEIHeadline"` — carries every `title/*` style, always at semibold. This is the display voice.
- **Text**: `font-family/text` → `"LGEIText"` — carries every other style (subtitle, body, cta, nav, badge), at either regular or semibold.
- Both are string-type primitive variables (`STRING`), meaning they're meant to be swapped as a unit if the brand typeface ever changes — components should bind to `{typography.title/*}` / the semantic style, never to a hardcoded family name.

### Size & Weight Primitives
| Token | Type | Value |
|---|---|---|
| `font-size/12` … `font-size/80` | NUMBER | 12, 14, 16, 20, 24, 32, 36, 56, 60, 80 |
| `font-weight/regular` | NUMBER | 400 |
| `font-weight/semibold` | NUMBER | 600 |

Ten discrete sizes and exactly two weights — there is no intermediate "medium" weight and no size between the named steps.

### Text Styles (13 total)

| Style | Size / LH | Weight | Family | Use (원문 그대로) |
|---|---|---|---|---|
| `title/xlarge` | 80 / 80 | 600 | headline | 대형 헤드라인 (large headline) |
| `title/large` | 60 / 60 | 600 | headline | Hero 헤드라인 |
| `title/medium` | 56 / 60 | 600 | headline | 섹션 타이틀 (section title) |
| `title/small` | 32 / 36 | 600 | headline | 카드·블록 타이틀 (card/block title) |
| `subtitle/large` | 36 / 42 | 400 | text | Hero 서브 카피 |
| `subtitle/medium` | 24 / 28 | 400 | text | 섹션 서브 카피 |
| `subtitle/medium-strong` | 24 / 28 | 600 | text | 강조 서브 카피 (emphasized subcopy) |
| `body/default` | 16 / 20 | 400 | text | 본문 (body) |
| `body/default-strong` | 16 / 20 | 600 | text | 본문 강조 (emphasized body) |
| `cta/medium` | 16 / 16 | 600 | text | 버튼 라벨 (button label) |
| `nav/menu` | 20 / 24 | 400 | text | 네비게이션 메뉴 |
| `badge/small` | 12 / 14 | 400 | text | 뱃지·라벨 (badge/label) |
| `body/small` | 14 / 16 | 400 | text | 보조 본문 (secondary body) |

### Principles

- **The headline/text split is a hard boundary.** Every `title/*` style is LGEIHeadline at semibold — no exceptions, no regular-weight titles. Everything else is LGEIText. This is a stricter rule than Apple's Display/Text split, which still allows the occasional cross-over (Apple's `display-md` runs on the *Text* face at display proportions); LG's sheet shows no such crossover.
- **Line-height is set in absolute px, not a multiplier**, and is frequently *tighter* than the font size at large sizes (`title/xlarge` 80/80, `title/large` 60/60) — headlines are meant to sit close together, the opposite of Apple's airy 1.07–1.19 display line-heights.
- **`cta/medium` is the only style whose line-height equals its font-size with no extra leading** (16/16) — a deliberate single-line-only constraint for button labels.
- **Letter-spacing is not used as a design lever anywhere in this sheet** — no style carries tracking, in contrast to Apple's signature negative-tracking headlines.

### Note on Font Substitutes
LGEIHeadline / LGEIText are LG's proprietary corporate faces and won't be present off-system:

- Use `'Noto Sans KR', system-ui, -apple-system, sans-serif` as the fallback stack — the sheet's own body copy is Korean, so any substitute must carry full Hangul coverage.
- Match weights literally: LGEIHeadline only ever needs its semibold cut; LGEIText needs regular and semibold. Don't synthesize a "bold" — none of the 13 styles call for it.
- Because line-heights are tighter than font-size at the top of the scale, a substitute with a larger default line-gap (many Latin-first fonts) will visually crowd less than the original intends — no correction is needed, but don't loosen the line-height to "fix" apparent tightness.

## Layout

### Spacing Scale (4px-multiple, 10 steps)

| Token | px | Cited usage |
|---|---|---|
| `spacing/4` | 4 | base unit |
| `spacing/8` | 8 | WSG Title Guide — Headline ↔ SubTitle |
| `spacing/12` | 12 | base unit |
| `spacing/16` | 16 | base unit |
| `spacing/20` | 20 | WSG Layout Common Principle — Title ↔ Content (Desktop) |
| `spacing/24` | 24 | Grid gutter / Body → Button |
| `spacing/32` | 32 | WSG Card Common Principle — Card margin (Desktop) |
| `spacing/40` | 40 | base unit |
| `spacing/48` | 48 | WSG Layout — Section top margin |
| `spacing/64` | 64 | WSG Layout — Section bottom margin (when a title is present) |

### Layout Widths (desktop reference px)

| Token | px | Cited usage |
|---|---|---|
| `layout/viewport` | 1920 | Full viewport width |
| `layout/banner` | 1600 | Banner area max width |
| `layout/container` | 1440 | Content container max width |
| `layout/gutter` | 24 | Grid column gutter |
| `layout/viewport-inset` | 240 | Viewport left/right margin = (1920 − 1440) / 2 |
| `layout/banner-inset` | 160 | Banner left/right margin = (1920 − 1600) / 2 |
| `layout/banner-padding` | 80 | Banner internal padding |
| `layout/filter-width` | 240 | Filter panel width |

Every layout width is derivable from `layout/viewport` (1920) and `layout/container` (1440) — the inset tokens are literally documented as the arithmetic between them, not independently chosen numbers. This is a fixed-width, centered-container desktop grid, not a fluid one.

## Elevation & Depth

There is **no elevation/box-shadow scale** in this token set — no `shadow/sm|md|lg`, no card-lift, no button-press shadow. The only tokens with "shadow" in the name are `shadow/disclaimer` and `shadow/disclaimer-inverse`, and both are **text-halo colors**, not drop shadows: a white or black halo placed behind fine-print/legal copy so it stays legible over photography, chosen to match the surface it sits on (white halo for dark text on light imagery, black halo for light text on dark imagery).

What *does* create depth here is surface substitution, and it's narrower than Apple's light/dark tile alternation:
- `bg/default` (white) → `bg/warm` (#F0ECE4) → `bg/subtle` (#F6F3EB) — three near-white steps used to separate adjacent sections without ever going dark.
- `surface/inverse` (#333333) is reserved specifically for the **GNB promotion bar** — a thin, narrow UI strip — not for full-page dark sections the way Apple's `surface-tile-1` alternates entire viewports.
- `surface/blur-blind` (white @ 60%) provides a translucent scrim/overlay treatment.

## Shapes

### Border Radius Scale

| Token | Value | Applies to (원문) |
|---|---|---|
| `radius/4` | 4px | Badge, Chip |
| `radius/6` | 6px | Button small (Contained) · Text Field |
| `radius/8` | 8px | Button medium (Contained) · Input |
| `radius/12` | 12px | Button large · frame-element rounding |
| `radius/28` | 28px | Card (Desktop) — WSG Card Common |
| `radius/full` | 9999px | Pill — Box Button, Toast (fully rounded) |

### Two Button Geometries
The scale encodes **two distinct button families**, not one size ladder:
1. **Contained buttons** — rectangular, radius scales *with* size: small `radius/6`, medium `radius/8`, large `radius/12`. Radius grows as the button grows.
2. **Box Buttons** (and Toasts) — always fully pilled at `radius/full`, regardless of size. A Box Button never borrows a Contained radius, and a Contained button never goes full-pill.

Don't cross the two families: if a CTA is meant to read as the primary "Box Button" (the pill CTA implied by `action/primary` + `action/primary-label`), it always uses `radius/full` — never `radius/6-12`.

## Components

> Reconstructed from the "적용 대상 / 용도" (applies-to / usage) column attached to each radius token and from the component-shaped semantic groups (`action/*`, `surface/toast-*`, `surface/card`, `surface/inverse`). No rendered button/card/input instances were present at the analyzed node — see **Known Gaps**.

**`button-box-primary`** — The primary commerce CTA ("Buy Now" per the source annotation on `action/primary`). Background `{colors.action/primary}`, label `{colors.action/primary-label}`, typography `{typography.cta/medium}`, rounded `{rounded.radius/full}`.

**`button-box-promo`** — Visually near-identical to the primary CTA but bound to `{colors.action/promo}` (ad-red, #FD312E) instead of `{colors.action/primary}` (#EA1917) — used specifically for advertising/promotional CTAs so the two intents stay separable in tracking even though a user can barely tell the reds apart.

**`button-box-secondary`** — Background `{colors.action/secondary}` (white), border `{colors.action/secondary-border}` (mid-gray-2), label `{colors.action/secondary-label}` (black), rounded `{rounded.radius/full}` — the ghost/secondary pairing to the primary Box Button.

**`button-contained-small/medium/large`** — The rectangular button family. Same `action/*` color roles as the Box Buttons, but radius scales with size (`radius/6` → `radius/8` → `radius/12`) instead of going full-pill.

**`text-field`** — Background `{colors.bg/default}`, border `{colors.border/default}` at rest, `{colors.border/focus}` on focus, rounded `{rounded.radius/6}` or `{rounded.radius/8}` (shared with the small/medium Contained buttons). Validation is surface-aware: on the standard white background use `{colors.state/success}` / `{colors.state/error}`; on `{colors.bg/warm}` specifically, switch to `{colors.state/success-on-warm}` / `{colors.state/error-on-warm}` — the standard state colors are documented as losing contrast on the warm surface.

**`badge-chip`** — Rounded `{rounded.radius/4}`, typography `{typography.badge/small}`. General badges use `{colors.flag/general}` (black); promotional badges use `{colors.flag/promotion}` (active-red) or the full `{colors.badge-gradient}` fill.

**`card`** — Background `{colors.surface/card}` (white), rounded `{rounded.radius/28}`, outer margin `{spacing.spacing/32}` on desktop (per "WSG Card Common Principle — Card margin").

**`toast-error` / `toast-warning` / `toast-info`** — Background `{colors.surface/toast-error|warning|info}`, text `{colors.text/on-toast-error|warning|info}`, rounded `{rounded.radius/full}` (grouped with Box Buttons in the radius sheet).

**`gnb-promotion-bar`** — The one place `{colors.surface/inverse}` (#333333) is used: a thin, dark promotional strip inside the global nav, with `{colors.text/inverse}` labels.

**`blur-blind-overlay`** — A translucent scrim using `{colors.surface/blur-blind}` (white @ 60%), for dimming content behind a modal/sheet without going fully opaque.

**`banner`** — Max width `{layout.layout/banner}` (1600px), left/right inset `{layout.layout/banner-inset}` (160px), internal padding `{layout.layout/banner-padding}` (80px).

**`section-container`** — Max width `{layout.layout/container}` (1440px) inside a `{layout.layout/viewport}` (1920px) frame, inset `{layout.layout/viewport-inset}` (240px), column gutter `{layout.layout/gutter}` (24px).

**`filter-panel`** — Fixed width `{layout.layout/filter-width}` (240px) — a left-rail filter/facet panel, sized identically to the viewport inset.

**`fine-print-disclaimer` / `fine-print-disclaimer-inverse`** — Legal/fine-print text over photography. Text `{colors.text/disclaimer}` (or `-inverse`) with a matching contrast halo `{colors.shadow/disclaimer}` (or `-inverse`) behind it.

## Do's and Don'ts

### Do
- Always resolve color through the semantic layer (`{colors.action/primary}`), never through the primitive it points to (`{colors.active-red}`) — the `←` provenance arrow exists so a primitive can be re-pointed later without touching every component.
- Use `{colors.state/success-on-warm}` and `{colors.state/error-on-warm}` for any input state sitting on `{colors.bg/warm}` — the plain `state/success`/`state/error` tokens are calibrated for white and lose contrast there.
- Keep `title/*` styles on **LGEIHeadline at semibold** and everything else on **LGEIText** — the two-face split is absolute, mirroring how Apple never mixes SF Pro Display and SF Pro Text within one role.
- Snap every spacing, layout, and radius value to the defined 4px-multiple ladder; there is nothing between tokens.
- Reserve `{colors.action/promo}` for advertising/promotional CTAs specifically — use `{colors.action/primary}` for standard commerce actions, even though the two reds are nearly indistinguishable to a user.
- Treat `{colors.badge-gradient}` as a fixed, non-variable brand asset — it's explicitly documented as unsupported for variable binding.

### Don't
- Don't cross the two button geometries: Box Buttons/Toasts are always `{rounded.radius/full}`; Contained buttons scale their radius with size (`radius/6 → 8 → 12`). Never apply a Contained radius to a pill CTA.
- Don't invent a font-weight between the two defined tokens (400/600) — there is no "medium," and none of the 13 text styles call for one.
- Don't use `{colors.surface/inverse}` as a general dark-mode page background — its only cited use is the GNB promotion bar, a thin strip, not a full-viewport dark tile.
- Don't use `{colors.text/disclaimer}` / `{colors.shadow/disclaimer}` outside legal/fine-print copy over photography — that pairing exists solely to solve that one contrast problem.
- Don't add letter-spacing to any text style — tracking is not a lever this system uses, unlike Apple's negative-tracking headlines.
- Don't treat the layout width tokens as independent choices — `layout/viewport-inset` and `layout/banner-inset` are documented as arithmetic derived from `layout/viewport` against `layout/container`/`layout/banner`; changing one without the other breaks the cited relationship.

## Responsive Behavior

The analyzed node defines **desktop reference values only** — `layout/viewport` (1920), `layout/banner` (1600), and `layout/container` (1440) are all fixed pixel widths, and every inset token is documented as arithmetic between two of these three numbers. No breakpoint tokens, no mobile/tablet width variants, and no responsive collapsing rules were present in this token sheet. Treat the layout block as the desktop baseline and see **Known Gaps** below before assuming any specific mobile behavior.

## Iteration Guide

1. Focus on one token category at a time, referencing its exact slash-path key (`{colors.action/primary}`, `{rounded.radius/28}`) — don't paraphrase a token name.
2. A semantic token is only ever a pointer to one primitive (the `←` column) — never assign a raw hex directly to a semantic key; add or repoint the primitive instead.
3. New semantic tokens must follow the established category grammar — `bg/`, `surface/`, `text/`, `border/`, `brand/`, `state/`, `icon/`, `flag/`, `action/`, `shadow/` — don't introduce a new top-level category without strong justification.
4. All spacing, layout, and radius values must land on an already-defined multiple of 4 — no off-ladder or fractional values.
5. `title/*` is always LGEIHeadline/Semibold; everything else is LGEIText at Regular or SemiBold. Never mix families within a role.
6. The badge gradient is the only gradient and the only place a raw, non-variable hex value is acceptable — everywhere else, bind to a token.
7. When documenting a new component, cite it the way this sheet cites radius/spacing usage (e.g. "Card (Desktop) — WSG Card Common") so the rationale for the value travels with the token, not just the number.

## Known Gaps

- This analysis covers only the "tokens" foundation frame (Color / Typography / Spacing & Layout / Radius) at the specified node. No button, card, toast, or input **mockups** were present there — the Components section above is reconstructed from the "적용 대상/용도" (applies-to/usage) annotations on each radius and semantic token, not from rendered component instances. Exact padding, heights, and pressed/hover states are therefore undocumented.
- No elevation/box-shadow scale exists anywhere in the analyzed tokens. The only "shadow"-named tokens are text-halo colors for legal copy over photography — there is no card-lift or button-press shadow token to document.
- No responsive breakpoint tokens were found. All `layout/*` values are fixed desktop pixel references; mobile/tablet behavior is undocumented at this node.
- `logo-gray` and `white-60` are grouped under the **Primary** primitive category in the source rather than **Gray Scale** — likely a file-organization choice rather than an intentional semantic grouping; don't over-read significance into that placement.
- The font-weight ladder defines exactly two weight variables (400/600), but the sheet's own page headline ("LG Typography Foundation") is itself styled with a "Bold" style-name outside that ladder — a labeling quirk of the underlying font file, not a documented third weight token.
- `badge-chip`'s own background/text colors are not explicitly bound in the analyzed sheet — only its radius (`radius/4`) is cited. The `flag/general` and `flag/promotion` tokens are the closest documented candidates for its accent color.
- Dark-mode counterparts for any of the semantic tokens were not surfaced — this sheet documents a single (light-dominant) theme.
