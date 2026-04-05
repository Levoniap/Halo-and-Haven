# Halo & Haven — Shopify Homepage Sections
## How to add these to your Craft theme

### Step 1 — Upload the CSS asset
1. In Shopify Admin go to **Online Store → Themes → Edit code**
2. Open the **Assets** folder
3. Click **Add a new asset** → paste the contents of `assets/hh-styles.css`
4. Name it `hh-styles.css` and save

### Step 2 — Upload each section
For each file in the `sections/` folder:
1. Open the **Sections** folder in the theme editor
2. Click **Add a new section**
3. Paste the contents of the file, name it exactly as listed below, and save

| File | Section name in Shopify |
|---|---|
| `sections/hh-hero.liquid` | `hh-hero` |
| `sections/hh-pillars.liquid` | `hh-pillars` |
| `sections/hh-editorial.liquid` | `hh-editorial` |
| `sections/hh-pullquote.liquid` | `hh-pullquote` |
| `sections/hh-club-haven.liquid` | `hh-club-haven` |

### Step 3 — Add sections to your homepage
1. Go to **Online Store → Themes → Customize**
2. Select **Home page**
3. Click **Add section** and search for each `HH —` section
4. Drag them into order (see recommended order below)
5. Fill in the settings for each section

---

## Recommended homepage order

1. **Announcement bar** *(existing)*
2. **HH — Hero** — full-screen dark hero with heading & CTA
3. **HH — Brand Pillars** — Light · Haven · Intention
4. **HH — Editorial** — brand story teaser with image (flip: off)
5. **Featured collection** *(existing Craft section — your journals)*
6. **HH — Pull Quote** — Lora italic brand quote
7. **HH — Editorial** *(second instance, flip: on)* — journal craftsmanship/detail
8. **HH — Club Haven** — email signup
9. **Footer** *(existing)*

---

## Brand Colours (reference)
| Name | Hex |
|---|---|
| Parchment | `#F7F2EC` |
| Linen | `#EFE8DF` |
| Dusk Rose | `#D9B5A0` |
| Deep Rose | `#C49A84` |
| Warm Clay | `#4A3828` |
| Near Black | `#2C2018` |

## Fonts
- **Cormorant Garamond** — headings (weights 300 & 400)
- **Jost** — body & navigation (weights 200 & 300)
- **Lora Italic** — pull quotes only
