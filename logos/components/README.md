# The Lupaxa Project SVG Components

This set is sized for practical rendering inside GitHub README content areas.

## Shared banner styling

Used by most section banners (`header.svg`, badges, etc.):

- Canvas: `1600 × 220`
- Background: `#203959`
- Border: `#6D95D3`
- Border width: `2px`
- Border geometry: `x="1" y="1" width="1598" height="218"`
- Primary text: `34px`, weight `600`
- Secondary text: `22px`, weight `400`
- Font stack: GitHub-compatible system sans-serif
- Text colour: `#FFFFFF`

The larger text compensates for GitHub scaling a 1600px-wide SVG down to the README content width.

## Footer styling

Footer assets (`footer.svg`, `footer-no-padding.svg`, `footer-for-child-orgs.svg`)
follow the portal footer rather than the bordered banner chrome:

- Background: `#203959`
- Top rule: white at `12%` opacity (`2px`)
- Border: `#6D95D3`, `2px` (inset `1px` so the stroke sits on the bar edge)
- Copyright: `26px`, weight `600` / name weight `700`, white at `90%` opacity
- Taglines: `26px`, weight `300`, white (same size as copyright — portal ratio)
- Copy: `© 2025-2026 The Lupaxa Project. All rights reserved.` plus the two brand taglines
- `footer.svg` / `footer-for-child-orgs.svg`: `20px` transparent padding above the bar
- `footer-no-padding.svg`: flush to the top edge
- `footer-for-child-orgs.svg`: adds a `PART OF` eyebrow in `#6D95D3`

## Root README usage

```html
<img
    src="./logos/components/footer.svg"
    alt="The Lupaxa Project Footer"
    width="100%"
/>
```

## Markdown file inside `docs/`

```html
<img
    src="../logos/components/footer.svg"
    alt="The Lupaxa Project Footer"
    width="100%"
/>
```

## Divider assets

- `divider.svg`: full-width 2px accent rule
- `divider-inset.svg`: 2px accent rule inset by 20px
