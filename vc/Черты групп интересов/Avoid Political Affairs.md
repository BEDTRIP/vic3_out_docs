---
type: concept
description: "Черта группы интересов «Avoid Political Affairs» — VC 1.13, `ig_trait_pragmatism`"
project: vic3
audience: agent
source: vc
aliases: ["Avoid Political Affairs", "ig_trait_pragmatism"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_pragmatism
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Avoid Political Affairs

Черта группы интересов · `ig_trait_pragmatism` · `common/interest_group_traits/joi_group_traits.txt:1005`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/treasury_bonds.dds`
- **min_approval**: `loyal`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-loyalists-from-political-movements-mult|state_loyalists_from_political_movements_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.15`
