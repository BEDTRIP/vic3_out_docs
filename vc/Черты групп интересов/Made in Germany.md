---
type: concept
description: "Черта группы интересов «Made in Germany» — VC 1.15, `ig_trait_made_in_germany`"
project: vic3
audience: agent
source: vc
aliases: ["Made in Germany", "ig_trait_made_in_germany"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_made_in_germany
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Made in Germany

Черта группы интересов · `ig_trait_made_in_germany` · `common/interest_group_traits/joi_group_traits.txt:441`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/engines_of_progress.dds`
- **min_approval**: `happy`
- **modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-tools-mult|goods_output_tools_mult]] = `0.1` → [[vanilla/Товары/Инструменты|Инструменты]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-steel-mult|goods_output_steel_mult]] = `0.1` → [[vanilla/Товары/Сталь|Сталь]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-manufacturing-throughput-add|building_group_bg_manufacturing_throughput_add]] = `0.05`
