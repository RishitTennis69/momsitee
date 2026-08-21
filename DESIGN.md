---
name: "The Smile Journal"
description: "Clinical field notes for calm family reading and precise editorial work."
colors:
  clinical-teal: "#0f7168"
  clinical-teal-deep: "#174a45"
  clinical-teal-tint: "#dcece8"
  clinical-teal-wash: "#edf6f3"
  field-note-brass: "#a77b34"
  desk-brass: "#9a7440"
  reader-ground: "#f7f9f7"
  admin-ground: "#f5f7f5"
  paper: "#fcfdfb"
  admin-paper-secondary: "#f7f9f7"
  reader-rule: "#d8dfdc"
  admin-rule: "#d7dfdb"
  reader-rule-soft: "#e7ece9"
  admin-rule-soft: "#e5ebe8"
  reader-graphite: "#20302d"
  admin-graphite: "#21302d"
  graphite-muted: "#53615e"
  graphite-quiet: "#65716d"
  success: "#23675f"
  success-wash: "#e4f0ed"
  danger: "#9a4d4d"
  danger-wash: "#f8eeee"
typography:
  display:
    fontFamily: "Onest, Segoe UI, sans-serif"
    fontSize: "clamp(48px, 7vw, 88px)"
    fontWeight: 650
    lineHeight: 0.96
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Onest, Segoe UI, sans-serif"
    fontSize: "clamp(30px, 4vw, 46px)"
    fontWeight: 640
    lineHeight: 1
    letterSpacing: "-0.04em"
  title:
    fontFamily: "Onest, Segoe UI, sans-serif"
    fontSize: "clamp(18px, 2vw, 23px)"
    fontWeight: 620
    lineHeight: 1.18
    letterSpacing: "-0.025em"
  body:
    fontFamily: "Onest, Segoe UI, sans-serif"
    fontSize: "17px"
    fontWeight: 430
    lineHeight: 1.82
  label:
    fontFamily: "Onest, Segoe UI, sans-serif"
    fontSize: "12px"
    fontWeight: 650
    lineHeight: 1.2
    letterSpacing: "0.07em"
rounded:
  square: "0"
  field: "4px"
  control: "5px"
  panel: "7px"
  surface: "8px"
  brand: "9px"
  feature: "10px"
  large: "12px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "18px"
  xl: "28px"
  2xl: "34px"
  3xl: "48px"
  4xl: "64px"
components:
  button-primary:
    backgroundColor: "{colors.clinical-teal-deep}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "10px 22px"
    height: "40px"
  button-primary-hover:
    backgroundColor: "{colors.clinical-teal}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "10px 22px"
    height: "40px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.graphite-muted}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "9px 10px"
  field:
    backgroundColor: "{colors.admin-paper-secondary}"
    textColor: "{colors.admin-graphite}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "0 12px"
    height: "40px"
  reader-feature:
    backgroundColor: "{colors.clinical-teal-deep}"
    textColor: "{colors.paper}"
    rounded: "{rounded.feature}"
    padding: "clamp(34px, 5vw, 64px)"
  archive-row:
    backgroundColor: "transparent"
    textColor: "{colors.reader-graphite}"
    typography: "{typography.title}"
    rounded: "{rounded.square}"
    padding: "26px 0 24px"
  admin-nav-item:
    backgroundColor: "transparent"
    textColor: "{colors.graphite-muted}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "11px 12px"
  admin-nav-item-active:
    backgroundColor: "{colors.clinical-teal-tint}"
    textColor: "{colors.clinical-teal-deep}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "11px 12px"
---

# Design System: The Smile Journal

## Overview

**Creative North Star: "Clinical Field Notes"**

The Smile Journal treats pediatric dental guidance as calm, carefully edited field notes: warm near-white paper, graphite copy, deep clinical teal, fine structural rules, and a single humanist sans-serif voice. It is editorial without nostalgia and clinical without coldness. The system earns warmth through measured spacing, readable line lengths, and humane type rather than decoration.

One design system serves two modes. The reader is intentionally asymmetrical: a large teal-washed lead story sits beside a compact, image-free archive, then gives way to a generous long-form reading column. The admin is deliberately operational: a persistent left spine, tabular summaries, disciplined fields, and compact actions. Their compositions differ because their jobs differ, while their typography, palette, rules, controls, icon language, focus states, and motion grammar remain recognizably one world.

**Key Characteristics:**

- Warm-white grounds and paper surfaces with graphite text.
- Deep teal as the scarce clinical signal for identity, action, selection, and focus.
- Fine one-pixel rules carry structure; most surfaces remain flat.
- One Onest family handles display, reading, metadata, and controls.
- Reader asymmetry and admin density are complementary expressions of the same system.
- Motion is short, directional, and tied to state; reduced-motion preferences are honored.
- Icons are simple monochrome line SVGs; interface meaning never depends on emoji.

## Colors

The palette is a quiet clinical neutral field with one dominant teal voice, a rare dry-brass editorial note, and restrained semantic colors for operational feedback.

### Primary

- **Clinical Teal:** The main identity and interaction color. Use it for focus, links, selection lines, and high-value interactive emphasis.
- **Deep Clinical Teal:** The system's strongest plane. It carries the featured reader story and primary admin actions, with paper-white foregrounds.
- **Teal Tint:** A low-contrast selected-state field for admin navigation and focus support.
- **Teal Wash:** A quieter interaction wash for hover, empty-state, and contextual emphasis.

### Secondary

- **Field-note Brass:** A rare reader-side annotation color for editorial metadata, never a competing call to action.
- **Desk Brass:** The slightly quieter admin counterpart, reserved for publication context rather than navigation or buttons.

### Neutral

- **Reader Ground / Admin Ground:** Closely related warm-white canvases. The reader is fractionally brighter; the admin is fractionally denser to support long working sessions.
- **Paper / Admin Paper Secondary:** Paper is the principal surface; the secondary admin paper separates fields and tool areas without introducing card chrome.
- **Reader Rules / Admin Rules:** One-pixel structural lines tuned to each ground. Soft rules are used only inside dense lists or nested regions.
- **Reader Graphite / Admin Graphite:** Nearly identical dark copy colors tuned per surface. Muted and quiet graphite carry descriptions, metadata, placeholders, and secondary controls.
- **Success / Danger:** Reserved for publication status, destructive actions, and genuine feedback. Their washes support local state without coloring large surfaces.

### Named Rules

**The One Clinical Voice Rule.** Deep teal owns identity, action, active state, and focus. Brass and semantic colors must never compete with it for general navigation.

**The Near-White, Not Stark-White Rule.** Use the reader or admin ground for the canvas and paper for contained surfaces; pure white appears only where a focused field needs extra clarity.

**The Surface-Tuning Rule.** Reader and admin neutrals may retain their observed one-step differences, but new hues or alternate brand colors require a system-level decision.

## Typography

**Display Font:** Onest (with Segoe UI and sans-serif fallbacks)
**Body Font:** Onest (with Segoe UI and sans-serif fallbacks)
**Label Font:** Onest (with Segoe UI and sans-serif fallbacks)

**Character:** One humanist family creates continuity between approachable reading and precise operations. Character comes from optical scale, variable weights, compact display leading, and open body leading—not from a decorative font pairing.

### Hierarchy

- **Display** (650, fluid 48–88px, 0.96 line-height): Reader mastheads and the largest editorial statements. Use tight negative tracking and balanced wrapping.
- **Headline** (640, fluid 30–46px, 1 line-height): Admin view titles and major operational headings.
- **Title** (620, fluid 18–23px, 1.18 line-height): Archive story titles and high-priority content labels.
- **Body** (430, 17px, 1.82 line-height): Long-form article reading, held to approximately 68 characters per line. Compact supporting copy may step down to 13.5–16px with 1.55–1.7 leading.
- **Label** (650, 12px, 0.07em tracking): Section labels, table headers, metadata, and terse control text. Uppercase is reserved for small structural labels, not prose or ordinary buttons.

### Named Rules

**The One-Family Rule.** Do not introduce a serif, mono, or decorative display face. Establish hierarchy with scale, weight, tracking, and space inside Onest.

**The Reading-Air Rule.** Long-form copy stays near 68ch with generous leading; operational copy may be denser but must remain clearly subordinate to the task title.

## Layout

The reader uses a 1240px outer system with 28px desktop gutters. Its masthead is a two-column editorial composition, and its index uses a 12-column grid: the featured story spans seven columns while the archive occupies the remaining five. At 860px and below, both become full-width; at 600px, outer gutters contract to 18px and the title remains decisively large.

The admin uses a fixed 238px left spine and a flexible work area capped at 1360px. Main content receives fluid horizontal padding from 28px to 72px. The spine becomes a 64px horizontal bar below 980px; tables shed secondary columns and stacked statistics replace horizontal summaries below 720px. The editor keeps a broad writing pane beside a 280px metadata rail until responsive collapse.

Spacing follows an observed 4 / 8 / 12 / 18 / 28 / 34 / 48 / 64 rhythm. Use smaller steps inside controls, mid-scale steps between related groups, and 48–64px intervals to mark true editorial or task boundaries. Fine rules may bridge space when a container would create unnecessary chrome.

### Named Rules

**The Two Modes, One Grammar Rule.** Reader pages may be asymmetrical and spacious; admin pages may be dense and axial. Both must share the same type, color, rule, control, icon, focus, and motion vocabulary.

**The Rule Before Container Rule.** Prefer a one-pixel divider, whitespace, or alignment edge before introducing another bordered box.

## Elevation & Depth

The system is flat by default. Depth comes from tonal separation, overlap-free planes, borders, and spatial hierarchy. Shadows are restricted to the sticky reader navigation after scroll, the featured story's editorial plane, and the admin lock screen where separation is functionally useful. Standard archive rows, tables, editor panels, and sidebars do not float.

### Shadow Vocabulary

- **Scrolled navigation** (`0 8px 24px rgba(32,48,45,.06)`): A faint state response once the reader navigation separates from moving content.
- **Featured story** (`0 18px 50px rgba(23,74,69,.14)`): A quiet teal-cast shadow for the lead editorial plane; hover deepens it to `0 22px 56px rgba(23,74,69,.19)`.
- **Admin panel ambient** (`0 1px 2px rgba(22,47,42,.04), 0 10px 28px rgba(22,47,42,.05)`): Available only where an existing operational overlay or lock panel needs separation.
- **Lock screen** (`0 24px 60px rgba(23,74,69,.10)`): The strongest shadow in the system, isolated to the sign-in panel.

### Named Rules

**The Flat-by-Default Rule.** No shadow is allowed merely to make a surface feel more designed. Use elevation only when it explains sticky, featured, or overlay behavior.

## Shapes

The form language is nearly rectilinear. Underlined navigation, category tabs, archive rows, badges, and table bands use square corners. Fields and compact controls use 4–5px radii; panels use 7–8px; brand marks use 9px; rare feature and lock surfaces use 10–12px. Fine one-pixel borders are preferred, with no capsule silhouettes.

**The Small-Corner Rule.** Radius follows scale but remains quiet. Do not increase radii to make the interface friendlier; warmth comes from type, color, and spacing.

**The No-Pill Rule.** Status, category, and navigation states use text, rules, tint, or compact rectangles—not rounded capsules.

## Components

### Buttons

Buttons are quiet, decisive, and compact.

- **Shape:** Compact controls use a 5px radius; reader text actions are often square and underlined.
- **Primary:** Deep clinical teal with paper-white text, typically 40–44px high and padded 16–22px horizontally.
- **Hover / Focus:** Hover shifts toward clinical teal; active presses scale to 0.98. Keyboard focus uses a 3px translucent teal outline with a 3px offset.
- **Ghost:** Transparent, graphite-muted, and aligned to the surrounding spine or rule. Hover adds only a pale neutral or teal wash.
- **Destructive:** Danger color appears only on the relevant action and its hover/wash, never as a general button theme.

### Fields

Fields are paper-like working surfaces rather than floating controls.

- **Style:** 40–44px high, 4px corners, one-pixel rule, secondary paper background, and 12–14px horizontal padding.
- **Focus:** Clinical teal border, pure-white local surface, and a subtle 3px teal focus ring.
- **Error / Disabled:** Error uses danger stroke and wash. Disabled styling should reduce contrast while preserving the field boundary and label legibility.

### Navigation

The reader navigation is a 68px sticky paper bar with a fine bottom rule, compact brand mark, and underlined Admin link. The admin navigation is a 238px operational spine with full-width 5px-corner rows; active state uses teal tint and deep teal text. Below 980px it becomes a 64px horizontal bar, and below 720px its actions may resolve to icon-only controls with accessible names.

### Category Tabs

Reader topics are text tabs, not chips. They use transparent backgrounds, generous horizontal gaps, and a one-pixel teal underline that scales from the left on selection. Hover changes text color; active state adds weight without adding a filled capsule.

### Featured Story

The lead story is the signature reader component: a seven-column, deep-teal plane with a restrained desaturated cover under a flat teal wash. Its content is distributed vertically, its title is large and compact, and its only lift is a two-pixel hover rise plus a slight image scale. It becomes full-width below 860px.

### Archive Rows

Secondary stories form an image-free vertical archive. Each row uses transparent background, square edges, a fine bottom rule, and horizontal movement of only 3px on hover. The title, metadata, excerpt, and read-more affordance—not card chrome—carry hierarchy.

### Tables and Status

Admin tables are open bands bounded by top and bottom rules. Rows sit on paper, hover with a pale clinical wash, and progressively hide lower-priority columns on narrow screens. Publication badges are unboxed text with a small monochrome status dot; action icons remain small, line-based, and locally colored only on hover.

## Do's and Don'ts

### Do:

- **Do** use Onest across display, body, metadata, fields, and controls.
- **Do** use one-pixel rules, whitespace, and alignment as the primary structure.
- **Do** preserve reader asymmetry and the admin's operational spine as surface-appropriate expressions of one system.
- **Do** keep teal scarce enough to retain authority, and reserve semantic colors for real status or risk.
- **Do** use monochrome inline SVG icons with visible focus and accessible names.
- **Do** keep transitions between 120ms and 220ms for controls, with the 420ms image transform reserved for the featured story; honor reduced-motion preferences.

### Don't:

- **Don't** introduce gradients, textures, glass, heavy blur, or decorative technology effects.
- **Don't** turn categories, statuses, navigation, or metadata into pills.
- **Don't** add generic image cards to the archive or stock-dashboard cards to the admin.
- **Don't** add a second typeface, colorful icon set, or emoji as interface iconography.
- **Don't** use shadow when a rule, tone, spacing interval, or alignment edge can explain the hierarchy.
- **Don't** flatten reader and admin into the same composition; unify their grammar, not their task density.
