<p align="center">
    <a href="https://github.com/the-lupaxa-project">
        <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/organisations/the-lupaxa-project/readme-logo.png" alt="Organisation Logo" />
    </a>
</p>

<h1 align="center">Brand Assets</h1>

The **Brand Assets** repository is the canonical source for the official branding assets used throughout **The Lupaxa Project** ecosystem.

It provides a central location for the project's core branding together with the official logos used by every GitHub organisation. Referencing assets directly
from this repository helps maintain a consistent visual identity across repositories, documentation, websites, presentations and other public-facing materials.

## Repository Contents

This repository currently contains:

- Official Lupaxa core logos
- GitHub organisation logos
- Repository README logos
- Transparent logo variants
- White logo variants

Additional branding assets may be introduced as the ecosystem evolves.

## Asset Catalogue

| Asset              | Location                                      | Purpose                                           |
| :----------------- | :-------------------------------------------- | :------------------------------------------------ |
| Core Logos         | `logos/core/`                                 | Official Lupaxa branding in multiple resolutions. |
| Organisation Logos | `logos/organisations/`                        | Official branding for each GitHub organisation.   |
| README Logos       | `logos/organisations/*/readme-logo*.png`      | Standard repository header logos.                 |
| Transparent Logos  | `logos/organisations/*/logo-transparent.png`  | General-purpose branding assets.                  |
| White Logos        | `logos/organisations/*/logo-white.png`        | Branding for white backgrounds.                   |

## Repository Structure

This section provides a high-level overview of the primary image assets contained within this repository. It is intended to illustrate the main categories of
logos and reusable branding components available, rather than provide a comprehensive inventory of every file. For a complete visual catalogue of all available
assets, including previews and detailed information, see the documentation in the docs directory.

```text
brand-assets
└── logos
    ├── core
    │   ├── 64
    │   ├── 128
    │   ├── 256
    │   ├── 320
    │   ├── 384
    │   └── 512
    └── organisations
        ├── actions-toolbox
        ├── api-extractor-toolbox
        ├── aws-toolbox
        ├── azure-toolbox
        ├── cicd-toolbox
        ├── code-playground
        ├── database-toolbox
        ├── developers-toolbox
        ├── devops-toolbox
        ├── docker-toolbox
        ├── gcp-toolbox
        ├── gh-toolbox
        ├── git-hooks-toolbox
        ├── git-toolbox
        ├── monitoring-toolbox
        ├── notifications-toolbox
        ├── security-toolbox
        ├── spider-toolbox
        ├── sre-toolbox
        ├── terraform-toolbox
        ├── the-lupaxa-lab
        ├── the-lupaxa-project
        └── the-lupaxa-project-private
```

## Documentation

Additional documentation is available within the [docs](docs/) directory.

## Referencing Assets

Repositories are encouraged to reference assets directly from this repository rather than storing duplicate copies.

For example:

```html
<img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/organisations/the-lupaxa-project/readme-logo.png" alt="The Lupaxa Project Logo" />
```

Using a shared source ensures that branding updates are automatically reflected throughout the ecosystem while reducing unnecessary duplication.

<a href="https://github.com/the-lupaxa-project">
    <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/components/footer.svg" alt="The Lupaxa Project Footer" width="100%" />
</a>
