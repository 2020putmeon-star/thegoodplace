# thegoodplace design system

Locked visual system for the poster shop. Hallmark runs should defer to this file.

## Genre
Atmospheric / lifestyle e-commerce

## Palette
| Token | Value | Use |
| --- | --- | --- |
| `--color-ink` | `#121816` | Primary text |
| `--color-ink-soft` | `#3a4540` | Secondary text |
| `--color-paper` | `#f3f7f6` | Page ground |
| `--color-mist` | `#e6eef0` | Soft ground |
| `--color-sage` / `--color-sage-deep` | `#2f5d4e` / `#1e3d33` | Brand, CTAs |
| `--color-teal` | `#1a7a74` | Accent / focus |
| `--color-mint` | `#9fd6cf` | On-dark accent |

## Typography
- Brand: Syne
- Display: Noto Serif TC
- Body: Noto Sans TC
- No italic headers; emphasis via weight or accent color

## Structure
- Home: photographic hero + catalogue grid + lookbook strip
- Nav: edge-aligned minimal wordmark + links
- Footer: statement close (“牆面值得被好好對待。”)

## Motion
- Prefer `opacity` / `transform`
- Respect `prefers-reduced-motion`
- Hero drift + lookbook marquee only when motion is allowed
