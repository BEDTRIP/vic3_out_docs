---
type: concept
description: "Метод производства «Small Stockpile» — T&R 1.13, `pm_nuclear_stockpile_1`"
project: vic3
source: tr
aliases: ["Small Stockpile", "pm_nuclear_stockpile_1"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nuclear_stockpile_1
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Small Stockpile

Метод производства · `pm_nuclear_stockpile_1` · `common/production_methods/ztr_military_production_methods.txt:510`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/chemical_artillery.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_good_uranium_add` = `100` → [[tr/Товары/Uranium|Uranium]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-from-army-power-projection-mult|country_prestige_from_army_power_projection_mult]] = `0.02`
- **timed_modifiers**: `pm_offense_defense_readjustment`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Stockpile Size|Stockpile Size]]
