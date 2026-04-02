---
title: Finish UUIDs
head:
  - - meta
    - property: og:title
      content: Finish UUIDs
  - - meta
    - name: description
      content: The Finish UUIDs Data Model describes per-finish unique identifiers for a card in an alternate language.
  - - meta
    - property: og:description
      content: The Finish UUIDs Data Model describes per-finish unique identifiers for a card in an alternate language.
  - - meta
    - name: keywords
      content: mtg, magic the gathering, mtgjson, json, finish uuids
---

# Finish UUIDs

The Finish UUIDs Data Model describes per-finish unique identifiers for a card in an alternate language.

- **Parent model:** [Foreign Data](/data-models/foreign-data/)
- **Parent property:** `skuIds`

## TypeScript Model

::: details Toggle Model {open}

<<< @/public/types/FinishUuids.ts{TypeScript}

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
