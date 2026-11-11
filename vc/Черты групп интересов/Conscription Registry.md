---
type: concept
description: "Черта группы интересов «Conscription Registry» — VC 1.15, `ig_trait_register_for_army`"
project: vic3
audience: agent
source: vc
aliases: ["Conscription Registry", "ig_trait_register_for_army"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_register_for_army
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Conscription Registry

Черта группы интересов · `ig_trait_register_for_army` · `common/interest_group_traits/joi_group_traits.txt:599`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/veteran_consultation.dds`
- **min_approval**: `happy`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-military-goods-cost-mult|country_military_goods_cost_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-conscription-rate-mult|state_conscription_rate_mult]] = `0.5`
