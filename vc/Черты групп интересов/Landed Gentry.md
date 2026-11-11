---
type: concept
description: "Черта группы интересов «Landed Gentry» — VC 1.15, `ig_trait_owner_of_land`"
project: vic3
audience: agent
source: vc
aliases: ["Landed Gentry", "ig_trait_owner_of_land"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_owner_of_land
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Landed Gentry

Черта группы интересов · `ig_trait_owner_of_land` · `common/interest_group_traits/joi_group_traits.txt:620`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/noblesse_oblige.dds`
- **min_approval**: `loyal`
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-efficiency-mult|state_aristocrats_investment_pool_efficiency_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы B#^m-building-rye-farm-throughput-add|building_rye_farm_throughput_add]] = `0.1` → [[vc/Здания/Ржаные поля|Ржаные поля]]
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.05`
