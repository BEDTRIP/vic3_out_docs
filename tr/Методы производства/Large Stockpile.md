---
type: concept
description: "Метод производства «Large Stockpile» — T&R 1.13, `pm_nuclear_stockpile_3`"
project: vic3
audience: agent
source: tr
aliases: ["Large Stockpile", "pm_nuclear_stockpile_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nuclear_stockpile_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Large Stockpile

Метод производства · `pm_nuclear_stockpile_3` · `common/production_methods/ztr_military_production_methods.txt:552`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/chemical_artillery.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_good_uranium_add` = `300` → [[tr/Товары/Uranium|Uranium]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-from-army-power-projection-mult|country_prestige_from_army_power_projection_mult]] = `0.05`
- **timed_modifiers**: `pm_offense_defense_readjustment`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Stockpile Size|Stockpile Size]]
