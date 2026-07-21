<p align="center">
    <a href="https://github.com/the-lupaxa-project">
        <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/organisations/the-lupaxa-project/readme-logo.png" alt="The Lupaxa Project Logo" />
    </a>
</p>

<h1 align="center">Official Colour Palette</h1>

The **Lupaxa Project** uses a simple, consistent colour palette throughout its branding to provide a recognisable and professional visual identity across the
entire ecosystem.

These colours should be used consistently throughout GitHub repositories, documentation, websites, presentations, applications, and other project materials
wherever practical.

## Palette at a Glance

| Primary                                                                      | Secondary                                                                        | Accent                                                                     | Black                                                                    | White                                                                    |
| :--------------------------------------------------------------------------: | :------------------------------------------------------------------------------: | :------------------------------------------------------------------------: | :----------------------------------------------------------------------: | :----------------------------------------------------------------------: |
| <img src="../logos/palette/primary-border.png" alt="primary"><br />`#111A32` | <img src="../logos/palette/secondary-border.png" alt="secondary"><br />`#203959` | <img src="../logos/palette/accent-border.png" alt="accent"><br />`#6D95D3` | <img src="../logos/palette/black-border.png" alt="black"><br />`#000000` | <img src="../logos/palette/white-border.png" alt="white"><br />`#FFFFFF` |

## Palette Overview

| Colour      | Preview                                                                      | Hex       | RGB             | Typical Use                                                          |
| :---------- | :--------------------------------------------------------------------------: | :-------: | :-------------- | :------------------------------------------------------------------- |
| Dark Blue   | <img src="../logos/palette/primary-border.png" width="32" alt="primary">     | `#111A32` | `17, 26, 50`    | Primary branding, headers, navigation bars and dark backgrounds.     |
| Middle Blue | <img src="../logos/palette/secondary-border.png" width="32" alt="secondary"> | `#203959` | `32, 57, 89`    | Primary accent colour for buttons, highlights and branding elements. |
| Light Blue  | <img src="../logos/palette/accent-border.png" width="32" alt="accent">       | `#6D95D3` | `109, 149, 211` | Secondary accent colour for links, emphasis and supporting graphics. |
| Black       | <img src="../logos/palette/black-border.png" width="32" alt="black">         | `#000000` | `0, 0, 0`       | Monochrome branding, typography and simplified graphics.             |
| White       | <img src="../logos/palette/white-border.png" width="32" alt="white">         | `#FFFFFF` | `255, 255, 255` | Reverse branding, dark backgrounds and presentation themes.          |

## Colour Specifications

### Dark Blue

| Property | Value               |
| :------- | :------------------ |
| Hex      | `#111A32`           |
| RGB      | `17, 26, 50`        |
| CSS      | `rgb(17, 26, 50)`   |

Typical uses include:

- Primary branding
- Website headers
- Documentation headers
- Dark backgrounds
- Banners and promotional material

### Middle Blue

| Property | Value               |
| :------- | :------------------ |
| Hex      | `#203959`           |
| RGB      | `32, 57, 89`        |
| CSS      | `rgb(32, 57, 89)`   |

Typical uses include:

- Buttons
- Section headings
- Feature highlights
- GitHub badges
- Accent graphics

### Light Blue

| Property | Value                  |
| :------- | :--------------------- |
| Hex      | `#6D95D3`              |
| RGB      | `109, 149, 211`        |
| CSS      | `rgb(109, 149, 211)`   |

Typical uses include:

- Hyperlinks
- Secondary highlights
- Information panels
- Decorative elements

### Black

| Property | Value            |
| :------- | :--------------- |
| Hex      | `#000000`        |
| RGB      | `0, 0, 0`        |
| CSS      | `rgb(0, 0, 0)`   |

Typical uses include:

- Monochrome branding
- High-contrast typography
- Print media
- Icons

### White

| Property | Value                  |
| :------- | :--------------------- |
| Hex      | `#FFFFFF`              |
| RGB      | `255, 255, 255`        |
| CSS      | `rgb(255, 255, 255)`   |

Typical uses include:

- Reverse logos
- Dark themes
- Presentation slides
- High-contrast layouts

## CSS Variables

The following CSS variables may be used within websites, documentation themes and web applications.

```css
:root {
    --lupaxa-dark-blue:   #111A32;
    --lupaxa-middle-blue: #203959;
    --lupaxa-light-blue:  #6D95D3;

    --lupaxa-black:       #000000;
    --lupaxa-white:       #FFFFFF;
}
```

## SCSS Variables

```scss
$lupaxa-dark-blue:   #111A32;
$lupaxa-middle-blue: #203959;
$lupaxa-light-blue:  #6D95D3;

$lupaxa-black:       #000000;
$lupaxa-white:       #FFFFFF;
```

## Example CSS

```css
body {
    background: #FFFFFF;
    color: #111A32;
}

header {
    background: #111A32;
    color: #FFFFFF;
}

a {
    color: #6D95D3;
}

.button {
    background: #203959;
    color: #FFFFFF;
}
```

## Example HTML

```html
<div
    style="
        background:#111A32;
        color:#FFFFFF;
        padding:1rem;
        border-radius:6px;">
    The Lupaxa Project
</div>
```

## Example GitHub Badge

```html
<img src="https://img.shields.io/badge/Get%20Support-203959?style=for-the-badge" />
```

Produces:

```html
<img src="https://img.shields.io/badge/Get%20Support-203959?style=for-the-badge" alt="Example Badge" />
```

## Accessibility Recommendations

When creating new branding assets:

- Use the transparent logo on light backgrounds.
- Use the white logo on dark backgrounds.
- Maintain strong foreground/background contrast.
- Avoid placing logos over complex or busy imagery.
- Ensure hyperlinks remain clearly distinguishable from surrounding text.
- Preserve adequate whitespace around all branding elements.

## Recommended Colour Usage

| Colour      | Primary Branding | Secondary Branding | UI Elements | Text | Backgrounds |
| :---------- | :--------------: | :----------------: | :---------: | :--: | :---------: |
| Dark Blue   | ✓                |                    | ✓           | ✓    | ✓           |
| Middle Blue |                  | ✓                  | ✓           |      |             |
| Light Blue  |                  | ✓                  | ✓           |      |             |
| Black       | ✓                |                    | ✓           | ✓    |             |
| White       | ✓                |                    | ✓           | ✓    | ✓           |

## Design Principles

To maintain a consistent visual identity across The Lupaxa Project:

- Use the official colour palette whenever practical.
- Avoid introducing additional primary brand colours.
- Preserve sufficient contrast between foreground and background colours.
- Use accent colours sparingly to maintain visual hierarchy.
- Keep branding clean, consistent and uncluttered.

<a href="https://github.com/the-lupaxa-project">
    <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/components/footer.svg" alt="The Lupaxa Project Footer" width="100%" />
</a>
