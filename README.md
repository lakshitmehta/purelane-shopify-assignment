# Purelane Shopify Assignment

Shopify theme implementation for the Troopod AI Product Engineer assignment.

## Overview

Rebuilt the required Purelane homepage sections from the supplied prototype using Shopify Dawn as the base theme.

### Implemented sections

- Purelane Hero
- Product Grid
- Best-selling Combos
- Bundles
- Reviews Rail

The sections are merchant-editable through the Shopify Theme Editor and use Shopify product data for product presentation.

## Shopify setup

- Base theme: Shopify Dawn
- Store type: Shopify development store
- Products seeded: 8
- Collection: `Purelane Products`

The seeded products intentionally include:

- In-stock products
- A sold-out product
- A product without an image
- A product with an unusually long title

These cases were used to test card/layout resilience.

## Theme structure

```text
sections/
├── purelane-hero.liquid
├── purelane-product-grid.liquid
├── purelane-combos.liquid
├── purelane-bundles.liquid
└── purelane-reviews.liquid

snippets/
└── purelane-product-card.liquid

templates/
└── index.json