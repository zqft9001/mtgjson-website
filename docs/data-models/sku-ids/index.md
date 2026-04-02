---
title: SKU IDs
head:
  - - meta
    - property: og:title
      content: SKU IDs
  - - meta
    - name: description
      content: The SKU IDs Data Model describes the unique identifiers for each finish variant of a card printing at a specific language.
  - - meta
    - property: og:description
      content: The SKU IDs Data Model describes the unique identifiers for each finish variant of a card printing at a specific language.
  - - meta
    - name: keywords
      content: mtg, magic the gathering, mtgjson, json, sku ids
---

# SKU IDs

The SKU IDs Data Model describes the unique identifiers for each finish variant of a card printing at a specific language.

- **Parent model:** [Card (Deck)](/data-models/card/card-deck/), [Card (Set)](/data-models/card/card-set/), [Card (Token)](/data-models/card/card-token/), [Foreign Data](/data-models/foreign-data/)
- **Parent property:** `skuIds`

## TypeScript Model

::: details Toggle Model {open}

<<< @/public/types/SkuIds.ts{TypeScript}

:::

## Model Properties

> ### etched <DocBadge type="warning" text="optional" />
>
> The UUID for the etched finish variant.
>
> - **Type:** `string`
> - **Introduced:** `v5.3.0`

> ### foil <DocBadge type="warning" text="optional" />
>
> The UUID for the foil finish variant.
>
> - **Type:** `string`
> - **Introduced:** `v5.3.0`

> ### nonfoil <DocBadge type="warning" text="optional" />
>
> The UUID for the nonfoil finish variant.
>
> - **Type:** `string`
> - **Introduced:** `v5.3.0`

> ### other <DocBadge type="warning" text="optional" />
>
> The UUID for any other finish variant.
>
> - **Type:** `string`
> - **Introduced:** `v5.3.0`

> ### signed <DocBadge type="warning" text="optional" />
>
> The UUID for the signed finish variant.
>
> - **Type:** `string`
> - **Introduced:** `v5.3.0`
