# Auto-Workspace-AI Website

## The Mathematical Architecture of Business Operations

**Live Preview**: Enable GitHub Pages to see this site live.

---

## Overview

This is the complete website for Auto-Workspace-AI, built as static HTML/CSS with interactive JavaScript simulators. The site is designed for direct GitHub Pages deployment or conversion to WordPress.

### Design System

- **Glass Morphism** with layered depth (darker panes in back, lighter in front)
- **Top-Lit 3D** — Light source from above, bright edges on top fading to shadows
- **Color-Coded Zones**:
  - 🔵 **Theory (Blue)** — Deep research, axioms, proofs
  - 🟠 **Articles (Orange/Fire)** — Applied insights, case studies
  - 🔴 **Social (Red)** — Distribution, key insights
  - 🟣 **Simulators (Purple)** — Interactive tools

---

## Structure

```
├── index.html                    # Home page
├── css/
│   └── design-system.css        # Complete design system
├── pages/
│   ├── theory/
│   │   └── index.html           # Theory section (blue zone)
│   └── articles/
│       └── index.html           # Articles section (orange zone)
├── simulators/
│   ├── index.html               # Simulators index
│   └── viability.html           # Viability Simulator (interactive)
└── assets/                       # Images, fonts, etc.
```

---

## The Math

This site presents **Business Field Theory** — a complete mathematical framework derived from Intent Tensor Theory.

### Core Equations

```
σ(n) = σ(n-1) + σ_θ · (1 - 𝒜(n))     # Residue accumulation
ℒ(n) = λ · Tr(M(n)) / 𝒜(n)²          # Lock capacity
V(n) = ℒ(n) - σ(n)                    # Viability

Identity persists ⟺ V > 0
Transition (Δ) occurs when V = 0
```

### Key Quantities

| Symbol | Name | Meaning |
|--------|------|---------|
| Φ | Distinction Potential | Strategic intent |
| σ | Residue | Accumulated organizational debt |
| 𝒜 | Alignment | Strategy-execution coherence |
| ℒ | Lock | Organizational resilience capacity |
| M | Memory | Institutional knowledge |
| V | Viability | Buffer before restructuring |
| Δ | Transition | Pivot/restructure event |
| ρ_q | Value | Crystallized worth at boundaries |

---

## Deployment

### GitHub Pages

1. Go to repo Settings → Pages
2. Source: Deploy from branch `main`
3. Folder: `/ (root)`
4. Site will be live at `https://sensei-intent-tensor.github.io/0.0_auto_workspace_ai_wordpress/`

### WordPress Migration

The HTML structure is designed for easy migration:
- Each page can become a WordPress page/template
- CSS can be loaded via theme or plugin
- Simulators work as embedded iframes or JavaScript includes

---

## Development

### Adding New Pages

1. Copy an existing page as template
2. Update navigation links
3. Apply appropriate zone class (`card-theory`, `card-articles`, etc.)
4. Push to repo

### Adding New Simulators

1. Copy `simulators/viability.html` as template
2. Implement the relevant equations in JavaScript
3. Add to `simulators/index.html`
4. Push to repo

---

## Related Repositories

- **Executable Physics**: [0.0._Executable_Physics](https://github.com/Sensei-Intent-Tensor/0.0._Executable_Physics) — The complete axiomatic foundation
- **Business Math Principals**: [0.0_business_math_foundation_principals](https://github.com/Sensei-Intent-Tensor/0.0_business_math_foundation_principals) — Applied business mathematics

---

## Philosophy

> "We don't claim to know better. We claim to *define* better."

No hand-waving. Real equations. Real definitions. Things that compute.

---

## License

MIT License

---

© 2025 Auto-Workspace-AI
