# Mateba Brand Colours

Status: active brand source of truth  
Last reviewed: 2026-05-05  
Applies to: mateba.co.za  
Primary reference asset: `assets/logos/mateba-logo-primary.jpg`

## Brand Colour Direction

The Mateba visual identity is based on a restrained premium palette: near-black typography, warm gold accents, soft ivory backgrounds, and neutral greys.

The palette should feel personal, refined, calm, and emotionally serious. It should not feel loud, synthetic, playful, or novelty-driven.

## Primary Palette

| Role | Colour | Hex | Usage |
|---|---:|---:|---|
| Primary text | Near black | `#171717` | Headings, body text, logo text, high-contrast interface elements |
| Deep black | Soft black | `#101010` | Buttons, footer backgrounds, strong visual anchors |
| Accent gold | Warm muted gold | `#B9915A` | Highlights, small dividers, CTAs, icon accents, brand emphasis |
| Soft gold | Pale champagne gold | `#D6B98A` | Secondary accents, hover states, subtle decorative elements |
| Background | Warm ivory | `#F8F5EF` | Main website background |
| Card background | Soft white | `#FFFFFF` | Cards, content blocks, form fields |
| Muted text | Warm grey | `#55504A` | Supporting copy, captions, secondary information |
| Border | Soft beige-grey | `#DED6CA` | Borders, separators, subtle UI lines |

## Recommended CSS Variables

```css
:root {
  --mateba-bg: #F8F5EF;
  --mateba-card: #FFFFFF;
  --mateba-text: #171717;
  --mateba-deep: #101010;
  --mateba-muted: #55504A;
  --mateba-gold: #B9915A;
  --mateba-gold-soft: #D6B98A;
  --mateba-border: #DED6CA;
}