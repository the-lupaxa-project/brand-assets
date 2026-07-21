# The Lupaxa Project SVG Components

This set is sized for practical rendering inside GitHub README content areas.

## Shared banner styling

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
