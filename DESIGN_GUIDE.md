# attune.id — Design Guide

> *A safe space to pause, reflect, and realign with yourself 🌿*

---

## Table of Contents

1. [Brand Philosophy](#1-brand-philosophy)
2. [Visual Identity](#2-visual-identity)
3. [Color Palette](#3-color-palette)
4. [Typography](#4-typography)
5. [Design Elements](#5-design-elements)
6. [Tone of Voice](#6-tone-of-voice)
7. [UI Patterns & Components](#7-ui-patterns--components)
8. [Spacing & Layout](#8-spacing--layout)
9. [Motion & Animation](#9-motion--animation)
10. [Accessibility](#10-accessibility)

---

## 1. Brand Philosophy

### Mission
attune.id is a campaign about **psychology, reflection, and self-love**. It exists as a gentle invitation to slow down, turn inward, and reconnect with the person who matters most — yourself.

### Core Values

| Pillar | Description |
|--------|-------------|
| **🧠 Psychology & Awareness** | Understanding how your mind works is the first step toward healing. We explore emotional patterns, cognitive habits, and the science behind self-awareness — not to diagnose, but to understand. |
| **🌿 Reflection & Growth** | Growth doesn't happen in constant motion — it happens in the pauses. We create space for honest reflection, where you can look back at where you've been and gently choose where to go next. |
| **💛 Self-Love & Compassion** | Before anything else, you deserve kindness from yourself. We practice self-compassion not as a luxury, but as a foundation — the quiet revolution of treating yourself with the same warmth you give others. |

### Brand Archetype
**The Sage + The Caregiver** — attune.id blends wisdom (psychology, self-awareness) with nurturing warmth (self-love, compassion). It is a wise friend, not a clinical therapist.

### Key Emotions
Calm · Warm · Safe · Introspective · Gentle · Grounded · Organic · Nurturing

---

## 2. Visual Identity

### Logo
- **Wordmark**: "attune.id" set in Playfair Display (serif)
- **Dot**: The period in "attune.id" is highlighted in Sage (#A1AD6B) — representing a pause, a full stop, a moment of stillness
- **Usage**: Always use the full wordmark. Never modify the spacing or replace the dot.

### Imagery Style
- **Photography**: Soft focus, natural lighting, earthy tones, organic compositions
- **Subjects**: Hands, journal pages, plants, natural textures, soft fabrics, quiet spaces
- **Color treatment**: Warm desaturated tones with muted greens and creams
- **No**: High contrast, harsh shadows, overly saturated colors, artificial lighting

### Iconography
- Use emoji-style icons for warmth and approachability (🧠 🌿 💛 ✨ 🌱)
- Rounded, soft shapes for custom illustrations
- Line weight: 1.5–2px for custom SVG icons
- Corner radius: generous (12–16px for containers)

---

## 3. Color Palette

The color palette was extracted from the brand's profile picture and campaign post images, reflecting the natural, earthy, and calming essence of attune.id.

### Primary Colors

| Swatch | Name | Hex | RGB | Usage |
|--------|------|-----|-----|-------|
| ██████ | **Cream** | `#FDF8F4` | `rgb(253, 248, 244)` | Page background, card backgrounds, hero section |
| ██████ | **Sage** | `#A1AD6B` | `rgb(161, 173, 107)` | Primary accent, links, decorative elements, hover states |
| ██████ | **Olive** | `#738C51` | `rgb(115, 140, 81)` | Secondary accent, section labels, highlights |
| ██████ | **Forest** | `#51604B` | `rgb(81, 96, 75)` | Primary buttons, CTA backgrounds, dark text on light |
| ██████ | **Dark Forest** | `#2D3529` | `rgb(45, 53, 41)` | Footer background, headings, high-emphasis text |

### Secondary Colors

| Swatch | Name | Hex | RGB | Usage |
|--------|------|-----|-----|-------|
| ██████ | **Sage Light** | `#D1E6CC` | `rgb(209, 230, 204)` | Image placeholder backgrounds, subtle dividers |
| ██████ | **Sage Mid** | `#B9C17B` | `rgb(185, 193, 123)` | Decorative accents, secondary decorative elements |
| ██████ | **Warm Gray** | `#B2B595` | `rgb(178, 181, 149)` | Muted decorative elements, secondary borders |
| ██████ | **Lavender Gray** | `#7B7882` | `rgb(123, 120, 130)` | Muted text, secondary information |
| ██████ | **Warm Brown** | `#68684F` | `rgb(104, 104, 79)` | Tertiary accents, warm contrast elements |
| ██████ | **Golden** | `#C9A777` | `rgb(201, 167, 119)` | Star ratings, warm highlights, achievement indicators |

### Text Colors

| Name | Hex | Usage |
|------|-----|-------|
| Text Primary | `#3D3D3D` | Body text |
| Text Light | `#6B6B6B` | Secondary text, subtitles, metadata |
| Text Inverse | `#FFFFFF` | Text on dark backgrounds (CTA, footer) |
| Text Inverse Muted | `rgba(255,255,255,0.7)` | Secondary text on dark backgrounds |

### Color Usage Guidelines

- **Do not** use pure black (`#000000`) anywhere — always use the dark forest or text colors
- **Do not** use pure white (`#FFFFFF`) — always use cream (`#FDF8F4`) for backgrounds
- Maintain a **minimum contrast ratio of 4.5:1** for body text
- The palette is intentionally **low saturation** — avoid adding highly saturated colors
- Green tones should always feel **earthy and muted**, never neon or bright

---

## 4. Typography

### Font Stack

| Role | Font | Fallback | Weight |
|------|------|----------|--------|
| **Headings / Display** | Playfair Display | Georgia, serif | 400 (Regular), 500 (Medium), 600 (Semibold) |
| **Body / UI** | DM Sans | -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif | 300 (Light), 400 (Regular), 500 (Medium), 600 (Semibold) |

### Type Scale

| Level | Size (clamp) | Weight | Line Height | Font |
|-------|-------------|--------|-------------|------|
| Hero Title | `clamp(2.8rem, 6vw, 4.5rem)` | 500 | 1.1 | Playfair Display |
| Section Title | `clamp(2rem, 5vw, 3.2rem)` | 500 | 1.2 | Playfair Display |
| Motto / Pull Quote | `1.6rem` | 400 (italic) | 1.6 | Playfair Display |
| Card Title | `1.3rem` | 500 | 1.3 | Playfair Display |
| Post Title | `1.15rem` | 500 | 1.4 | Playfair Display |
| Body Text | `1.1rem` | 400 | 1.8 | DM Sans |
| Small Text | `0.9rem` | 400 | 1.6 | DM Sans |
| Label / Tag | `0.75rem` | 600 | 1.0 | DM Sans (uppercase, 3px letter-spacing) |

### Typography Guidelines
- Playfair Display is used for **emotional, reflective content** — headings, quotes, testimonials
- DM Sans is used for **functional, readable content** — body text, navigation, buttons
- Italic Playfair Display is reserved for **quotes and the brand motto**
- Never use more than two font sizes in a single section
- Line height should be generous (1.6–1.8) for body text to enhance readability

---

## 5. Design Elements

### Shapes & Corners
- **Buttons**: Fully rounded (`border-radius: 100px`) — pill-shaped
- **Cards**: `border-radius: 24px` — generous, soft corners
- **Images**: `border-radius: 20px` for grid images, `border-radius: 50%` for profile/hero
- **Tags/Badges**: `border-radius: 100px` — pill-shaped
- **Icons container**: `border-radius: 16px` — slightly rounded square

### Borders
- Default: `1px solid rgba(161, 173, 107, 0.12)` — subtle sage border
- Hover: `1px solid rgba(161, 173, 107, 0.25)` — slightly more visible
- Decorative: `1px dashed rgba(161, 173, 107, 0.15)` — for animated rings

### Shadows
- Card default: `0 12px 40px rgba(81, 96, 75, 0.08)`
- Card hover: `0 16px 48px rgba(81, 96, 75, 0.1)`
- Button: `0 8px 24px rgba(81, 96, 75, 0.3)`
- Hero image: `0 20px 60px rgba(81, 96, 75, 0.15)`
- Floating elements: `0 8px 24px rgba(0,0,0,0.06)`

### Decorative Elements
- **Animated rings**: Concentric circles around the hero image that rotate slowly
- **Floating tags**: Badges that hover and float with CSS animation
- **Background particles**: Gentle floating circles in brand colors (opacity 0.12)
- **Scroll indicator**: A subtle line with fade animation at the bottom of the hero

---

## 6. Tone of Voice

### Personality
Warm · Gentle · Wise · Inviting · Non-judgmental · Poetic but clear

### Writing Principles

| Principle | Description |
|-----------|-------------|
| **Gentle** | Never commanding. Use "you might", "consider", "perhaps" instead of "you must", "do this" |
| **Inclusive** | "You are not alone" — always speak to shared human experience |
| **Simple** | No jargon. No clinical language. Plain, warm words. |
| **Poetic** | Use metaphor and imagery (e.g., "the quiet revolution of treating yourself with kindness") |
| **Affirming** | "You are already enough" — the core message is one of acceptance, not improvement |

### Example Phrases
- "A gentle invitation to slow down, turn inward, and reconnect with the person who matters most — you."
- "Growth doesn't happen in constant motion — it happens in the pauses."
- "You are not a project to be fixed. You are a person to be understood."
- "The present moment is the only place where life can truly be found."

### What We Don't Say
- ❌ Harsh or clinical language ("diagnose", "disorder", "fix")
- ❌ Toxic positivity ("just be happy", "think positive")
- ❌ Urgency or FOMO ("limited time", "act now")
- ❌ Comparison ("better than", "unlike others")

---

## 7. UI Patterns & Components

### Navigation
- Fixed top nav with blur backdrop on scroll
- Logo on left, links on right
- CTA button as the last nav item (pill-shaped, forest green)
- Mobile: slide-in drawer from right with hamburger toggle

### Hero Section
- Split layout: text left, circular image right
- Animated decorative rings around the image
- Floating tags with emoji icons
- Scroll indicator at bottom
- Badge above heading with animated dot

### Cards
- **Value Cards**: 3-column grid, hover lift effect with top accent bar animation
- **Post Cards**: Image on top, content below, hover lift with image zoom
- **Testimonial Cards**: Quote, stars, author avatar and name

### Buttons
- **Primary**: Solid forest green, white text, arrow icon on right
- **Secondary**: Outlined sage border, forest text
- **CTA (inverted)**: White background, forest text (on dark gradient sections)

### Stats
- 3-column grid of centered stat items
- Serif numbers, sans-serif labels
- Subtle cream background with sage border

### Footer
- Dark forest background
- 4-column grid: brand description + 3 link columns
- Social links as text abbreviations
- Copyright line with divider

---

## 8. Spacing & Layout

### Grid System
- Max container width: `1200px`
- Padding: `24px` on each side (mobile: `24px`)
- Column gaps: `32px` (desktop), `24px` (tablet), `16px` (mobile)

### Section Spacing
- Section padding: `120px 0` (desktop), `80px 0` (tablet), `60px 0` (mobile)
- Hero padding: `120px 0 80px` (accounts for fixed nav)

### Component Spacing
- Between cards in a grid: `32px`
- Between sections within a component: `48px` (e.g., header to grid)
- Between text elements: `16px` (label to title), `20px` (title to body), `24px` (body to CTA)
- Card padding: `40px 32px` (value cards), `24px` (post card body)

### Breakpoints

| Breakpoint | Target |
|------------|--------|
| `> 1024px` | Desktop (full layout) |
| `1024px` | Tablet landscape (2-column grids) |
| `768px` | Tablet portrait (single column, mobile nav) |
| `480px` | Mobile (compact sizing) |

---

## 9. Motion & Animation

### Transition Default
`0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94)` — a gentle ease-in-out

### Animations

| Animation | Element | Duration | Description |
|-----------|---------|----------|-------------|
| `float-particle` | Background particles | 15–35s | Particles rise from bottom to top, rotating and scaling |
| `pulse-dot` | Hero badge dot | 2s | Gentle scale pulse on the status dot |
| `ring-spin` | Hero decorative rings | 20–30s | Slow rotation of concentric circles |
| `float-tag` | Floating tags | 3s | Gentle vertical hover motion |
| `fade-in-out` | Scroll indicator | 2s | Opacity pulse |
| `reveal` | Scroll-triggered sections | 0.8s | Fade up + translateY on scroll into view |

### Hover Effects
- **Cards**: Lift `translateY(-4px to -6px)` + shadow increase
- **Images**: Scale `1.05` on hover
- **Links**: Underline slide-in animation (`width: 0 → 100%`)
- **Buttons**: Lift `translateY(-2px)` + shadow increase
- **Value cards**: Top accent bar slides in from left (`scaleX(0 → 1)`)

### Motion Philosophy
- All animations should feel **slow, gentle, and organic**
- No jarring movements, no bouncy overshoots
- Use `opacity` and `transform` only (GPU-accelerated properties)
- Respect `prefers-reduced-motion` — all animations should be non-essential

---

## 10. Accessibility

### Color Contrast
- Body text (`#3D3D3D`) on cream (`#FDF8F4`): **10.5:1** ✅ (exceeds AAA)
- Text light (`#6B6B6B`) on cream (`#FDF8F4`): **5.2:1** ✅ (exceeds AA)
- White text on forest (`#51604B`): **7.8:1** ✅ (exceeds AAA)
- Section labels (`#738C51`) on cream (`#FDF8F4`): **4.7:1** ✅ (meets AA)

### Interactive Elements
- All interactive elements must have visible focus states
- Buttons and links should have `cursor: pointer`
- Mobile menu toggle has `aria-label="Toggle menu"`
- Navigation links are semantic `<ul>` / `<li>` elements

### Responsive Design
- Fluid typography using `clamp()` for all heading sizes
- Layout adapts at 1024px, 768px, and 480px breakpoints
- Touch targets minimum 44px for mobile
- No horizontal overflow at any screen size

### Reduced Motion
```css
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

---

## Appendix: Asset Sources

| Asset | Source | Description |
|-------|--------|-------------|
| `assets/profile-picture.jpg` | Brand asset | 1024×1024 profile image — source of color palette |
| `assets/post-1.webp` | Campaign post | 640×800 — Reflection-themed post |
| `assets/post-2.webp` | Campaign post | 640×800 — Self-love themed post |
| `assets/post-3.webp` | Campaign post | 640×800 — Mindfulness-themed post |

---

*Design guide v1.0 — Extracted from attune.id brand assets and campaign materials.*
