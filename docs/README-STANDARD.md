<p align="center">
    <a href="https://github.com/the-lupaxa-project">
        <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/organisations/the-lupaxa-project/readme-logo.png" alt="The Lupaxa Project Logo" />
    </a>
</p>

<h1 align="center">README Standard</h1>

This document defines the recommended structure and layout for README.md files across **The Lupaxa Project**. Following this standard provides a consistent
experience for users while maintaining a recognisable visual identity throughout the project.

## Objectives

The standard aims to:

- Provide a consistent appearance across all repositories
- Present information in a predictable order
- Reinforce **The Lupaxa Project** branding
- Keep documentation clean, simple and GitHub-native
- Minimise custom HTML while using reusable brand components where appropriate

## Standard Layout

A typical README should follow this structure:

```txt
Organisation Logo
Repository Title (H1)
Repository Description
(Optional)
Badges
Contents
Main Documentation
Footer
```

### 1. Organisation Logo

Each README begins with the logo for the organisation that owns the repository.

- Centre aligned
- Standard logo dimensions
- Shared visual style across all organisations
- Stored in the Brand Assets repository

The organisation logo identifies the specific organisation responsible for the repository.

Example:

```html
<p align="center">
    <a href="https://github.com/the-lupaxa-project">
        <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/organisations/the-lupaxa-project/readme-logo.png" alt="The Lupaxa Project Logo" />
    </a>
</p>
```

### 2. Repository Title

Use a centred H1 for the repository title.

Example:

```html
<h1 align="center">Repository Title</h1>
```

The repository title should describe the repository itself, not the organisation.

### 3. Repository Description

Immediately below the title, include a short description.

This should usually be one or two sentences explaining:

- What the repository contains
- Who it is intended for
- Its primary purpose

Example:

```txt
Official documentation for the reusable GitHub Actions maintained by The Lupaxa Project.
```

### 4. Badges (Optional)

Badges may be included where they provide useful information, for example:

- Documentation status
- Licence
- Release version
- Supported platforms
- Package manager availability

Avoid excessive use of badges.

Only include badges that provide meaningful information to users.

### 5. Contents

Longer READMEs should include a table of contents near the beginning of the document.

Shorter READMEs do not normally require one.

### 6. Main Documentation

Use standard GitHub Markdown wherever possible.

Recommended heading hierarchy:

```markdown
# Repository
## Section
### Subsection
#### Detail
```

Prefer native Markdown over custom HTML.

Use HTML only where Markdown cannot achieve the required result.

### 7. Footer

Every README should conclude with the standard Lupaxa footer.

The footer provides:

- A clear visual indication that the document has ended
- Consistent branding across all repositories
- Copyright attribution

The standard footer component is hosted in the Brand Assets repository.

Where appropriate, the footer image may be wrapped in a hyperlink to the relevant organisation or project.

Example:

```html
<a href="https://github.com/the-lupaxa-project">
    <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/components/footer.svg" alt="The Lupaxa Project Footer" width="100%" />
</a>
```

The standard footer.svg already includes the recommended spacing above the footer.

No additional spacing is normally required.

## Formatting Conventions

To provide a consistent experience across **The Lupaxa Project**, documentation should follow these conventions:

- References to **The Lupaxa Project** should always be shown in **bold**
- Document titles should use normal text with title capitalisation
- Repository names, filenames, directories, commands, labels and other literal values should use inline code formatting
- Use bold sparingly for emphasis outside of project branding
- Bullet lists consisting of words or short phrases should not end with full stops
- Bullet lists containing complete sentences should use appropriate punctuation
- Prefer standard GitHub Flavoured Markdown
- Use HTML only where Markdown cannot achieve the required result

## Reusable Components

Where practical, reusable branding components should be used in preference to duplicated markup or custom designs.

Shared assets, including logos, dividers and footers, are maintained within the Brand Assets repository to ensure consistency across **The Lupaxa Project**.

## Branding

Branding should be consistent, understated and purposeful.

The recommended approach is:

- Organisation branding at the beginning
- Repository documentation in the middle
- **The Lupaxa Project** branding at the end

Avoid repeating logos, banners or branding throughout the document.

Branding should support the documentation rather than distract from it.

## Design Principles

README files should be:

- Clear
- Concise
- Accessible
- Easy to scan
- GitHub-native in appearance
- Consistent across all repositories

Documentation should always remain the primary focus.

Branding should support the documentation, never distract from it.

## Future Changes

This standard may evolve over time as The Lupaxa Project grows.

Changes should aim to improve consistency while preserving compatibility with existing repositories wherever practical.

<a href="https://github.com/the-lupaxa-project">
    <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/components/footer.svg" alt="The Lupaxa Project Footer" width="100%" />
</a>
