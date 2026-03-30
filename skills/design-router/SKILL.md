---
name: design-router
description: Automatically routes to the best UI/UX design skills based on project type, industry, and aesthetic requirements. Acts as a design dispatcher that reads the UIUX-high-taste-skill collection and applies the right combination.
---

# Design Router — Intelligent Skill Dispatcher

## Purpose
When building any website, app, or interface, this skill analyzes the project context and automatically selects the most relevant design skills from the collection.

## How It Works

Before writing ANY design code:
1. Identify the **project type** (landing page, dashboard, portfolio, SaaS, etc.)
2. Identify the **industry/domain** (tech, luxury, health, finance, creative, etc.)
3. Identify the **aesthetic intent** (minimal, bold, editorial, raw, premium, etc.)
4. Route to the correct skill combination from the table below

## Routing Matrix

### By Project Type

| Project Type | Primary Skill | Secondary Skills | Rationale |
|-------------|--------------|-----------------|-----------|
| **SaaS / Dashboard** | `taste-skill` | `mrgoonie-design-system`, `mrgoonie-ui-styling` | Variance 8 + token architecture + shadcn components |
| **Landing Page** | `frontend-design` | `taste-skill`, `soft-skill` | Bold creative direction + anti-slop rules + luxury feel |
| **Portfolio / Agency** | `soft-skill` | `taste-skill`, `frontend-slides` | $150k agency aesthetic + anti-slop + presentations |
| **E-commerce** | `mrgoonie-ui-ux-pro-max` | `taste-skill`, `mrgoonie-brand` | UX guidelines + anti-slop + brand consistency |
| **Blog / Editorial** | `minimalist-skill` | `taste-skill` | Notion/Linear editorial feel + typography focus |
| **Data Dashboard** | `brutalist-skill` | `taste-skill`, `d3js-viz` | Industrial data density + anti-slop + D3 charts |
| **Corporate Site** | `taste-skill` | `mrgoonie-brand`, `mrgoonie-design-system` | Clean professional + brand guidelines + tokens |
| **Creative / Art** | `frontend-design` | `algorithmic-art`, `canvas-design` | Maximum creative freedom + generative art + premium fonts |
| **Presentation / Deck** | `mrgoonie-slides` | `frontend-slides`, `mrgoonie-design` | Slide strategies + HTML presentations + design routing |
| **Mobile App UI** | `mrgoonie-ui-ux-pro-max` | `mrgoonie-ui-styling` | 10 stacks supported + shadcn + accessibility |
| **Developer Tools** | `brutalist-skill` | `taste-skill`, `minimalist-skill` | Terminal aesthetic + monospace + clean UI |
| **Startup MVP** | `taste-skill` | `mrgoonie-ui-ux-pro-max`, `redesign-skill` | Fast premium output + UX rules + upgrade path |

### By Industry / Domain

| Industry | Aesthetic Direction | Skills to Load |
|----------|-------------------|----------------|
| **Tech / AI / SaaS** | Dark, glass, precise | `taste-skill` (Ethereal Glass vibe) + `mrgoonie-design-system` |
| **Luxury / Fashion** | Editorial, serif, warm | `soft-skill` (Editorial Luxury vibe) + `mrgoonie-brand` |
| **Health / Wellness** | Soft, airy, pastel | `soft-skill` (Soft Structuralism) + `minimalist-skill` |
| **Finance / Fintech** | Clean, data-dense, trustworthy | `minimalist-skill` + `mrgoonie-ui-ux-pro-max` + `d3js-viz` |
| **Creative Agency** | Bold, asymmetric, motion-heavy | `frontend-design` + `soft-skill` + `taste-skill` |
| **Developer / DevTools** | Raw, mono, terminal | `brutalist-skill` + `taste-skill` |
| **Real Estate / PropTech** | Professional, warm, data | `taste-skill` + `mrgoonie-design-system` + `d3js-viz` |
| **Education** | Clear, accessible, structured | `minimalist-skill` + `mrgoonie-ui-ux-pro-max` |
| **Gaming** | Dark, immersive, animated | `frontend-design` + `taste-skill` (motion intensity 8+) |
| **Food / Restaurant** | Warm, editorial, photography | `soft-skill` + `frontend-design` |

### By Aesthetic Intent

| Intent | Skill | Key Settings |
|--------|-------|-------------|
| "Make it look expensive" | `soft-skill` | Double-bezel cards, spring physics, serif headlines |
| "Make it clean and minimal" | `minimalist-skill` | Warm monochrome, bento grids, zero gradients |
| "Make it bold and unique" | `frontend-design` | Maximum creative freedom, unexpected choices |
| "Make it raw and technical" | `brutalist-skill` | Swiss typo, CRT effects, monospace dominant |
| "Make it professional" | `taste-skill` | Variance 6, density 4, neutral palette |
| "Make it modern SaaS" | `taste-skill` + `mrgoonie-design-system` | Token architecture, component specs |
| "Redesign/upgrade this" | `redesign-skill` | Audit existing → targeted fixes → polish |

## Universal Rules (Always Apply)

Regardless of which skills are routed:

1. **ALWAYS load `taste-skill`** as baseline anti-slop protection (banned fonts, colors, patterns)
2. **ALWAYS load `output-skill`** to prevent lazy/truncated output
3. **Check `redesign-skill`** if upgrading an existing project
4. **Check `mrgoonie-ui-ux-pro-max`** for accessibility and UX validation
5. **Use `stitch-skill`** when generating DESIGN.md for external tools (Stitch, Figma prompts)

## Execution Protocol

```
1. READ the user's request
2. IDENTIFY project type + industry + aesthetic
3. MATCH against routing matrix
4. LOAD the primary skill's full SKILL.md
5. SCAN secondary skills for relevant sections only
6. APPLY universal rules (taste-skill baseline + output-skill)
7. BUILD with the combined intelligence
```

## Skill Locations

All skills are in `skills/` directory of this repository:
- Leon: `taste-skill/`, `redesign-skill/`, `soft-skill/`, `minimalist-skill/`, `brutalist-skill/`, `stitch-skill/`, `output-skill/`
- mrgoonie: `mrgoonie-ui-ux-pro-max/`, `mrgoonie-design/`, `mrgoonie-design-system/`, `mrgoonie-ui-styling/`, `mrgoonie-brand/`, `mrgoonie-slides/`, `mrgoonie-banner-design/`
- Anthropic: `frontend-design/`, `canvas-design/`, `theme-factory/`, `algorithmic-art/`
- Community: `frontend-slides/`, `d3js-viz/`, `web-asset-generator/`
