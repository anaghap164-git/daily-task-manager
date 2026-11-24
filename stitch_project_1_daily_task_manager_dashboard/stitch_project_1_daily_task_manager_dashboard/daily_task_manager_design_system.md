---
name: "Daily Task Manager"
description: "A crisp, authoritative corporate SaaS design system built around deep navy blue, pure white surfaces, and cool light-grey canvases for daily operational clarity."
---

## Overview

Daily Task Manager is a professional business productivity application designed for team leads, operations managers, and individual contributors who need immediate clarity over their daily workload. The interface embodies a **Corporate / Modern** design style: calm, structured, and dependable, eliminating visual noise in favor of high-contrast typographic hierarchy, generous whitespace, and clear status signaling.

The emotional tone is focused and composed—using authoritative navy blue for primary navigation and key actions, pure white elevated cards for scannable metrics and task tables, and a cool light-grey canvas that reduces eye strain during extended desktop sessions.

## Colors

The palette pairs a deep, authoritative **Navy Blue** (`primary` and `primary-container`) with crisp **Pure White** cards (`surface-container-lowest`) set against a cool **Light Grey-Blue** canvas (`background` / `surface`). Semantic status colors—emerald green for completed work, warm amber for pending items, and crimson red for overdue or high-priority alerts—are reserved strictly for state communication and paired with soft container tints.

```yaml
colors:
  light:
    primary: "#022448"
    on-primary: "#FFFFFF"
    primary-container: "#1E3A5F"
    on-primary-container: "#8AA4CF"
    secondary: "#555F70"
    on-secondary: "#FFFFFF"
    secondary-container: "#D6E0F4"
    on-secondary-container: "#5A6374"
    tertiary: "#341F00"
    on-tertiary: "#FFFFFF"
    tertiary-container: "#503300"
    on-tertiary-container: "#C69B5F"
    error: "#B91C1C"
    on-error: "#FFFFFF"
    error-container: "#FFDAD6"
    on-error-container: "#93000B"
    background: "#F8F9FF"
    on-background: "#0B1C30"
    surface: "#F8F9FF"
    surface-dim: "#CBDBF5"
    surface-bright: "#F8F9FF"
    surface-container-lowest: "#FFFFFF"
    surface-container-low: "#EFF4FF"
    surface-container: "#E5EEFF"
    surface-container-high: "#DCE9FF"
    surface-container-highest: "#D3E4FE"
    on-surface: "#0B1C30"
    surface-variant: "#E0E2EB"
    on-surface-variant: "#43474E"
    outline: "#74777F"
    outline-variant: "#C4C6CF"
    inverse-surface: "#213145"
    inverse-on-surface: "#EAF1FF"
    inverse-primary: "#ADC8F5"
    shadow: "#000000"
    scrim: "#000000"
    success: "#006C4C"
    on-success: "#FFFFFF"
    success-container: "#89F8C7"
    on-success-container: "#002114"
    warning: "#A33D22"
    on-warning: "#FFFFFF"
    warning-container: "#FFDBD2"
    on-warning-container: "#3C0800"
  dark:
    primary: "#ADC8F5"
    on-primary: "#133155"
    primary-container: "#1E3A5F"
    on-primary-container: "#8AA4CF"
    secondary: "#BDC7DA"
    on-secondary: "#273140"
    secondary-container: "#40495A"
    on-secondary-container: "#AFB9CC"
    tertiary: "#EDBF7F"
    on-tertiary: "#452B00"
    tertiary-container: "#503300"
    on-tertiary-container: "#C69B5F"
    error: "#FFB4AB"
    on-error: "#690005"
    error-container: "#93000B"
    on-error-container: "#FFDAD6"
    background: "#031427"
    on-background: "#D3E4FE"
    surface: "#031427"
    surface-dim: "#031427"
    surface-bright: "#2A3A4F"
    surface-container-lowest: "#000F21"
    surface-container-low: "#0B1C30"
    surface-container: "#102034"
    surface-container-high: "#1B2B3F"
    surface-container-highest: "#26364A"
    on-surface: "#D3E4FE"
    surface-variant: "#43474E"
    on-surface-variant: "#C4C6CF"
    outline: "#8E9199"
    outline-variant: "#43474E"
    inverse-surface: "#D3E4FE"
    inverse-on-surface: "#213145"
    inverse-primary: "#455F87"
    shadow: "#000000"
    scrim: "#000000"
    success: "#6CDBAC"
    on-success: "#003826"
    success-container: "#005138"
    on-success-container: "#89F8C7"
    warning: "#FFB4A2"
    on-warning: "#611200"
    warning-container: "#83260D"
    on-warning-container: "#FFDBD2"
```

## Typography

The typographic system pairs **Mulish** for geometric, confident headings and KPI figures with **Instrument Sans** for crisp, highly legible interface labels, table cells, and body copy. **Source Code Pro** is reserved for tabular identifiers or date codes where monospaced alignment aids scanning. All numeric metrics and dates use `tabular-nums`.

```yaml
typography:
  display-sm:
    fontFamily: "Mulish"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 44px
    letterSpacing: -0.5px
  display-sm-mobile:
    fontFamily: "Mulish"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 34px
    letterSpacing: -0.25px
  headline-lg:
    fontFamily: "Mulish"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 34px
    letterSpacing: -0.25px
  headline-md:
    fontFamily: "Mulish"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 28px
    letterSpacing: -0.2px
  headline-sm:
    fontFamily: "Mulish"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 24px
    letterSpacing: 0px
  title-md:
    fontFamily: "Instrument Sans"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 22px
    letterSpacing: 0px
  title-sm:
    fontFamily: "Instrument Sans"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0px
  body-lg:
    fontFamily: "Instrument Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0px
  body-md:
    fontFamily: "Instrument Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0px
  body-sm:
    fontFamily: "Instrument Sans"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 18px
    letterSpacing: 0px
  label-lg:
    fontFamily: "Instrument Sans"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0.1px
  label-md:
    fontFamily: "Instrument Sans"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0.2px
  label-sm:
    fontFamily: "Instrument Sans"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 16px
    letterSpacing: 0.25px
  mono-sm:
    fontFamily: "Source Code Pro"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 18px
    letterSpacing: 0px
```

## Layout & Spacing

The desktop dashboard uses a persistent **240px Left Sidebar** paired with a **sticky Top Header** and a **fluid 12-column main content grid** (`24px` gutters, `24px` page margins) over the light-grey canvas. A strict `4px` / `8px` spacing scale governs internal card padding (`20px–24px`) and vertical section rhythm (`24px–32px`), keeping component internals distinct from page-level gaps. On smaller viewports (`< 1024px`), the sidebar collapses behind a drawer toggle and the 4-column summary KPI grid reflows to 2 columns or 1 column.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section: 32px
  page-margin: 24px
```

## Elevation & Depth

Hierarchy is established through **tonal surface layering** and **low-contrast ghost outlines** rather than heavy drop shadows. Pure white cards (`surface-container-lowest`) sit cleanly on the cool light-grey background (`surface`), separated by subtle `1px` borders (`outline-variant` at low opacity or solid) and a whisper-soft ambient shadow (`0 1px 3px rgba(11, 28, 48, 0.04)`). Interactive rows and buttons reveal depth on hover via subtle tonal shifts (`surface-container-low`).

## Shapes

The application uses approachable, modern **rounded corners** throughout. Cards and data tables use `12px` (`md`), interactive buttons and search inputs use `8px` (`DEFAULT`), compact icon buttons and checkboxes use `4px` (`sm`), and status or priority badges use `full` pill radii (`9999px`) for immediate visual distinction from rectangular controls.

```yaml
rounded:
  sm: 4px
  DEFAULT: 8px
  md: 12px
  lg: 16px
  xl: 24px
  full: 9999px
```

## Motion & Micro-interaction

Motion is crisp, purposeful, and understated. Hover and focus state transitions on buttons, sidebar items, and table rows resolve within `120ms` using `ease-out` so the workspace feels responsive. Modals and drawers enter over `220ms` with a decelerating curve and exit in `150ms`. Layout-shifting properties are never animated; only color, opacity, and transform are transitioned, respecting `prefers-reduced-motion`.

```yaml
motion:
  state-change:
    duration: 120ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 220ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
  surface-exit:
    duration: 150ms
    delay: 0ms
    timingFunction: cubic-bezier(0.3, 0, 1, 1)
```

## Voice & Content Strategy

Copy is **concise, direct, and action-oriented**.

- **Capitalisation:** Title Case for navigation items, page titles, and table column headers; Sentence case for task descriptions, empty states, and helper text.
- **Button & Action Labels:** Always start with a clear verb (`Add New Task`, `Edit Task`, `Mark Complete`). Never use generic labels like `Submit` or `OK`.
- **Numbers & Dates:** Use `tabular-nums` for all summary counts (`25`, `12`, `8`, `5`) and standard `MMM DD, YYYY` format (e.g., `Nov 23, 2026`) for Assigned Date and Due Date so columns align cleanly.
- **Empty & Error States:** State clearly what is missing and offer a single primary next step (e.g., "No tasks match your filter. Clear filters or add a new task.").

## Components

Component implementations live as individual HTML sticker sheet files in
`components/`. Each file contains the canonical, styled HTML components with
`<!-- COMPONENT: name -->` comment markers. Read each file before use.

- **Badge** → `@components/badge.html`: `badge-numeric`, `badge-dot`
- **Button** → `@components/button.html`: `button-primary`, `button-icon`, `button-with-icon`
- **Card** → `@components/card.html`: `card-elevated`, `card-action`, `card-interactive`, `card-interactive-2`
- **Searchbar** → `@components/searchbar.html`: `searchbar-standard`, `searchbar-with-suggestions`
- **Table** → `@components/table.html`: `table-standard`, `table-interactive`, `table-selectable`
