---
type: concept
description: "Черта группы интересов «Urban Suppliers» — VC 1.13, `ig_trait_urban_suppliers`"
project: vic3
audience: agent
source: vc
aliases: ["Urban Suppliers", "ig_trait_urban_suppliers"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_urban_suppliers
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Urban Suppliers

Черта группы интересов · `ig_trait_urban_suppliers` · `common/interest_group_traits/joi_group_traits.txt:2109`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/farmers_markets.dds`
- **min_approval**: `loyal`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-construction-goods-cost-mult|country_construction_goods_cost_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.15` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
