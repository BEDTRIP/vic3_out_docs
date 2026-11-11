---
type: concept
description: "Черта группы интересов «Romanticism» — VC 1.15, `ig_trait_romanticism`"
project: vic3
audience: agent
source: vc
aliases: ["Romanticism", "ig_trait_romanticism"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_romanticism
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Romanticism

Черта группы интересов · `ig_trait_romanticism` · `common/interest_group_traits/joi_group_traits.txt:189`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/propagandists.dds`
- **min_approval**: `loyal`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-society-tech-research-speed-mult|country_society_tech_research_speed_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-services-mult|goods_output_services_mult]] = `0.25` → [[vanilla/Товары/Услуги|Услуги]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-mult|goods_output_fine_art_mult]] = `0.25` → [[vanilla/Товары/Картины|Картины]]
