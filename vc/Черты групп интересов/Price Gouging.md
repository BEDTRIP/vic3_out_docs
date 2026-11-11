---
type: concept
description: "Черта группы интересов «Price Gouging» — VC 1.15, `ig_trait_against_imports`"
project: vic3
audience: agent
source: vc
aliases: ["Price Gouging", "ig_trait_against_imports"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_against_imports
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Price Gouging

Черта группы интересов · `ig_trait_against_imports` · `common/interest_group_traits/joi_group_traits.txt:294`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/old_ways.dds`
- **max_approval**: `unhappy`
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-food-security-add|state_food_security_add]] = `-0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `-0.1` → [[vc/Здания/Пищевые производства|Пищевые производства]]
