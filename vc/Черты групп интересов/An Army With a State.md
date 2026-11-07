---
type: concept
description: "Черта группы интересов «An Army With a State» — VC 1.13, `ig_trait_army_hasastate`"
project: vic3
audience: agent
source: vc
aliases: ["An Army With a State", "ig_trait_army_hasastate"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_army_hasastate
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# An Army With a State

Черта группы интересов · `ig_trait_army_hasastate` · `common/interest_group_traits/joi_group_traits.txt:409`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/patriotic_fervor.dds`
- **min_approval**: `loyal`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-war-exhaustion-casualties-mult|country_war_exhaustion_casualties_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.1`
