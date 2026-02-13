# Seniors DevCo Design System

## Core Colors

| Name | Hex | Usage |
|------|-----|-------|
| `forest` | `#0a1f1c` | Primary Background |
| `deep-green` | `#142d29` | Secondary Background, Sections |
| `background-dark` | `#050f0d` | Darker Backgrounds, Contrast |
| `copper` | `#b87333` | Accents, Links, Highlights |
| `copper-light` | `#d4a780` | Lighter accents |
| `silver` | `#c0c0c0` | Primary Text |
| `muted-silver` | `#8e9b97` | Secondary Text, Borders |
| `white` | `#ffffff` | Headings, High Contrast Text |

## Typography

### Font Families
- **Display:** "Playfair Display", serif
- **Body:** "Plus Jakarta Sans", sans-serif

### Usage
- **Headings (H1-H6):** `font-display tracking-tight`
- **Body Text:** `font-sans`
- **Navigation/Labels:** Uppercase, `tracking-widest` or `tracking-[0.x em]`

## UI Components

### Buttons
- **Primary:**
  - Background: `bg-copper`
  - Text: `text-forest`
  - Font: `font-black uppercase tracking-[0.5em] text-xs`
  - Hover: `hover:bg-white`

- **Secondary / Outline:**
  - Border: `border-white/20`
  - Text: `text-white`
  - Hover: `hover:border-copper hover:bg-copper/10`

- **Text Link:**
  - `group flex items-center gap-4 text-xs font-bold uppercase tracking-widest`
  - Includes an animated line: `<span class="w-12 h-px bg-copper group-hover:w-20 transition-all"></span>`

### Navigation
- **Top Bar:** `fixed top-0 left-0 right-0 z-50 mix-blend-difference px-6 py-8` (Transparent/blend mode)
- **Links:** Uppercase small text with high tracking (`tracking-[0.4em]`)

### Cards (Services/Process)
- **Service Item:**
  - Icon: Material Symbol in `text-copper`
  - Title: White text
  - List Items: `text-[10px] uppercase tracking-[0.2em]` with copper bullet points
- **Process Step:**
  - Border: `border-l border-white/10`
  - Number: Large display font `text-5xl text-copper/20`
  - Hover Effect: `hover:bg-forest`

## Utilities
- `.editorial-line`: 1px height, gradient from transparent to copper-50% to transparent.
- `.asymmetric-mask`: Specific polygon clip-path for images.
- `.text-vertical`: Vertical writing mode.

## Icons
- Library: Google Material Symbols Outlined
- Class: `material-symbols-outlined`
