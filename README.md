<svg viewBox="0 0 800 280" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg" style="display:block;margin:0 0 2rem 0;border-radius:12px;background:oklch(96% 0.012 80);font-family:system-ui,-apple-system,sans-serif">
  <defs>
    <style>
      @keyframes fadeUp {
        0% { opacity: 0; transform: translateY(16px); }
        100% { opacity: 1; transform: translateY(0); }
      }
      @keyframes fadeIn {
        0% { opacity: 0; }
        100% { opacity: 1; }
      }
      @keyframes slideIn {
        0% { transform: translateX(-20px); opacity: 0; }
        100% { transform: translateX(0); opacity: 1; }
      }
      @keyframes pulse {
        0%, 100% { opacity: 0.4; }
        50% { opacity: 1; }
      }
      @keyframes drawLine {
        0% { stroke-dashoffset: 200; }
        100% { stroke-dashoffset: 0; }
      }
      @keyframes float {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-6px); }
      }
      @keyframes scaleIn {
        0% { transform: scale(0.8); opacity: 0; }
        100% { transform: scale(1); opacity: 1; }
      }
      .fade-up { animation: fadeUp 0.6s cubic-bezier(0.16,1,0.3,1) forwards; opacity: 0; }
      .fade-in { animation: fadeIn 0.8s ease-out forwards; opacity: 0; }
      .slide-in { animation: slideIn 0.5s cubic-bezier(0.16,1,0.3,1) forwards; opacity: 0; }
      .pulse { animation: pulse 3s ease-in-out infinite; }
      .float { animation: float 4s ease-in-out infinite; }
      .scale-in { animation: scaleIn 0.5s cubic-bezier(0.16,1,0.3,1) forwards; opacity: 0; }
      .line { stroke-dasharray: 200; animation: drawLine 1.2s ease-out 0.3s forwards; }
      .d1 { animation-delay: 0.1s; }
      .d2 { animation-delay: 0.2s; }
      .d3 { animation-delay: 0.3s; }
      .d4 { animation-delay: 0.4s; }
      .d5 { animation-delay: 0.5s; }
      .d6 { animation-delay: 0.6s; }
      .d7 { animation-delay: 0.7s; }
      .d8 { animation-delay: 0.8s; }
    </style>
  </defs>

  <!-- Background shapes -->
  <rect x="0" y="0" width="800" height="280" rx="12" fill="oklch(96% 0.012 80)" />

  <!-- Subtle background dot pattern -->
  <g opacity="0.06" class="fade-in d1">
    <circle cx="60" cy="40" r="3" fill="oklch(40% 0.008 70)" />
    <circle cx="120" cy="80" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="200" cy="30" r="2.5" fill="oklch(40% 0.008 70)" />
    <circle cx="320" cy="55" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="450" cy="35" r="3" fill="oklch(40% 0.008 70)" />
    <circle cx="550" cy="70" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="680" cy="40" r="2.5" fill="oklch(40% 0.008 70)" />
    <circle cx="740" cy="90" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="40" cy="180" r="2.5" fill="oklch(40% 0.008 70)" />
    <circle cx="100" cy="230" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="700" cy="200" r="3" fill="oklch(40% 0.008 70)" />
    <circle cx="760" cy="240" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="300" cy="220" r="2" fill="oklch(40% 0.008 70)" />
    <circle cx="500" cy="250" r="2.5" fill="oklch(40% 0.008 70)" />
  </g>

  <!-- Decorative geometric elements -->
  <g class="fade-in d1">
    <rect x="48" y="48" width="32" height="32" rx="3" fill="none" stroke="oklch(60% 0.15 255 / 0.15)" stroke-width="1.5" />
    <rect x="52" y="52" width="24" height="24" rx="2" fill="oklch(60% 0.15 255 / 0.08)" />
  </g>
  <g class="fade-in d3">
    <rect x="720" y="48" width="32" height="32" rx="3" fill="none" stroke="oklch(60% 0.15 255 / 0.12)" stroke-width="1.5" />
  </g>

  <!-- Floating decorative element -->
  <g class="float" transform-origin="680 200">
    <rect x="660" y="180" width="28" height="28" rx="4" fill="oklch(60% 0.15 255 / 0.07)" stroke="oklch(60% 0.15 255 / 0.15)" stroke-width="1" />
  </g>

  <!-- Accent line -->
  <line x1="60" y1="68" x2="80" y2="68" stroke="oklch(58% 0.20 256)" stroke-width="2" stroke-linecap="round" class="line" />

  <!-- Title -->
  <text x="84" y="90" font-family="system-ui,-apple-system,sans-serif" font-size="12" font-weight="600" letter-spacing="0.12" fill="oklch(40% 0.008 70)" text-transform="uppercase" class="fade-up d2">Project</text>

  <text x="84" y="132" font-family="system-ui,-apple-system,sans-serif" font-size="48" font-weight="700" letter-spacing="-0.02" fill="oklch(22% 0.014 258)" class="fade-up d3">
    <tspan>gitt</tspan>
  </text>

  <text x="84" y="168" font-family="system-ui,-apple-system,sans-serif" font-size="18" font-weight="400" letter-spacing="0" fill="oklch(40% 0.008 70)" class="fade-up d4">Build. Ship. Iterate. <tspan fill="oklch(58% 0.20 256)" font-weight="500">—</tspan></text>

  <!-- Badge-style chips -->
  <g class="fade-up d5">
    <rect x="84" y="195" width="80" height="26" rx="4" fill="oklch(58% 0.20 256 / 0.12)" />
    <text x="124" y="212" font-family="ui-monospace,monospace" font-size="11" font-weight="500" fill="oklch(58% 0.20 256)" text-anchor="middle">opencode</text>
  </g>
  <g class="fade-up d6">
    <rect x="172" y="195" width="76" height="26" rx="4" fill="oklch(18% 0.010 60 / 0.06)" />
    <text x="210" y="212" font-family="ui-monospace,monospace" font-size="11" font-weight="500" fill="oklch(40% 0.008 70)" text-anchor="middle">hallmark</text>
  </g>
  <g class="fade-up d7">
    <rect x="256" y="195" width="64" height="26" rx="4" fill="oklch(18% 0.010 60 / 0.06)" />
    <text x="288" y="212" font-family="ui-monospace,monospace" font-size="11" font-weight="500" fill="oklch(40% 0.008 70)" text-anchor="middle">skills</text>
  </g>

  <!-- Right side decorative element -->
  <g class="scale-in d5" transform="translate(560, 60)">
    <rect x="0" y="0" width="180" height="160" rx="8" fill="oklch(18% 0.016 260)" />
    <rect x="12" y="12" width="8" height="8" rx="2" fill="oklch(80% 0.05 255 / 0.3)" />
    <rect x="28" y="12" width="8" height="8" rx="2" fill="oklch(80% 0.05 255 / 0.3)" />
    <rect x="44" y="12" width="8" height="8" rx="2" fill="oklch(80% 0.05 255 / 0.3)" />
    <text x="16" y="46" font-family="ui-monospace,monospace" font-size="11" fill="oklch(70% 0.02 255 / 0.5)">$</text>
    <text x="30" y="46" font-family="ui-monospace,monospace" font-size="11" fill="oklch(90% 0.02 255 / 0.8)">npx skills add nutlope/</text>
    <text x="16" y="66" font-family="ui-monospace,monospace" font-size="11" fill="oklch(58% 0.20 256)">hallmark</text>
    <text x="80" y="66" font-family="ui-monospace,monospace" font-size="11" fill="oklch(90% 0.02 255 / 0.6)">--agent opencode</text>
    <text x="16" y="90" font-family="ui-monospace,monospace" font-size="11" fill="oklch(70% 0.02 255 / 0.5)">✓</text>
    <text x="30" y="90" font-family="ui-monospace,monospace" font-size="11" fill="oklch(80% 0.05 255 / 0.6)">Installed 1 skill</text>
    <rect x="16" y="104" width="148" height="1" fill="oklch(70% 0.02 255 / 0.12)" />
    <text x="16" y="124" font-family="ui-monospace,monospace" font-size="10" fill="oklch(70% 0.02 255 / 0.4)">hallmark · anti-AI-slop</text>
    <text x="16" y="140" font-family="ui-monospace,monospace" font-size="10" fill="oklch(70% 0.02 255 / 0.4)">design skill</text>
  </g>
</svg>

<div align="center">

[![License](https://img.shields.io/badge/license-MIT-2563EB?style=flat&labelColor=1A1A2E)](LICENSE)
![Status](https://img.shields.io/badge/status-active-6B7280?style=flat&labelColor=1A1A2E)

</div>

A design-forward project scaffold built with [opencode](https://opencode.ai) skills. Uses **Hallmark** — an anti-AI-slop design skill that generates UIs that look *made*, not generated.

<br>

---

<br>

## Contents

- [Philosophy](#philosophy)
- [Stack](#stack)
- [Getting started](#getting-started)
- [Design system](#design-system)
- [Architecture](#architecture)
- [Contributing](#contributing)

<br>

## Philosophy

Three principles guide everything built here.

**Structural variety.** Two pages for two different briefs should not share the same hero → features → CTA → footer rhythm. Every macrostructure is a deliberate choice, not a template default.

**Disciplined color.** One accent, used on less than 3 % of any viewport. Tinted paper. Tinted ink. No `#000`, no `#fff`. OKLCH everywhere.

**Honest copy.** Real numbers, real testimonials, or a placeholder. No invented metrics, no fabricated logos, no "trusted by 50,000+ teams."

<details>
<summary>Design tenets</summary>

<br>

| Tenet | Practice |
|---|---|
| **Typography purity** | No italic headers. Roman display faces only. A 2+1 font ceiling — display, body, one outlier. |
| **Motion discipline** | Animate only `transform` and `opacity`. Three easing curves. Three duration buckets. Reduced-motion as a hard requirement. |
| **Asymmetric layout** | Left-biased, right-biased, top-heavy, or bottom-weighted. Centre-biased is a default, never a choice. |
| **Pre-emit self-critique** | Every artifact scored 1–5 on Philosophy, Hierarchy, Execution, Specificity, Restraint, Variety. Any score below 3 triggers a revision pass. |

</details>

<br>

## Stack

| Layer | Choice |
|---|---|
| Agent runtime | opencode |
| Design skill | Hallmark v1.1 |
| Color space | OKLCH (perceptually uniform) |
| Font pairing | Fraunces (display) · Geist (body) · Geist Mono (outlier) |
| Motion | CSS transforms + opacity via `cubic-bezier(0.16, 1, 0.3, 1)` |
| Responsive | 320 / 375 / 414 / 768 px — verified, no horizontal scroll |

<br>

## Getting started

```sh
# Clone the repository
git clone https://github.com/your-org/gitt
cd gitt

# The .agents directory contains Hallmark and any installed skills
ls .agents/skills/
```

### Using Hallmark

```sh
# Default design flow — builds a new page
npx skills add <org/repo>

# Audit an existing page
hallmark audit <target>

# Redesign with a specific mood
hallmark redesign <target> --mood <name>

# Study a design's DNA from a URL or screenshot
hallmark study <url-or-screenshot>
```

<br>

## Design system

The color palette follows OKLCH perceptually-uniform construction:

```css
:root {
  --color-paper:      oklch(96 %  0.012  80);
  --color-paper-2:    oklch(93 %  0.014  80);
  --color-rule:       oklch(82 %  0.010  80);
  --color-neutral:    oklch(56 %  0.008  80);
  --color-muted:      oklch(40 %  0.008  70);
  --color-ink:        oklch(18 %  0.010  60);
  --color-accent:     oklch(58 %  0.20  256);
  --color-focus:      oklch(55 %  0.19  55);
}
```

| Token | Role |
|---|---|
| `--color-paper` | Base surface (tinted warm) |
| `--color-accent` | Electric cobalt — links, active states, focus rings |
| `--color-ink` | Primary text (charcoal, not black) |
| `--color-rule` | Hairline borders |

Type scale uses a major-third ratio (1.25) from a 16 px base.

<br>

## Architecture

```
.
+-- .agents/
|   +-- skills/
|       +-- hallmark/          # Hallmark design skill
|           +-- references/    # Design rules, tokens, themes
|           +-- SKILL.md       # Skill manifest
+-- README.md
```

<br>

## Contributing

This project follows Hallmark's discipline. Before contributing, review the [anti-patterns reference](.agents/skills/hallmark/references/anti-patterns.md) to understand what the skill rejects.

- No purple-to-cyan gradients
- No re-drawn browser chrome
- No italic headers
- No invented metrics
- No Inter, Roboto, or Open Sans

---

<div align="center">
  <sub>Built with opencode · Designed with Hallmark</sub>
</div>
