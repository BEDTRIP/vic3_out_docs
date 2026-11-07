---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_eiffel_tower)» — ваниль 1.13, `pm_default_building_eiffel_tower`"
project: vic3
source: vanilla
aliases: ["Стандартное производство (pm_default_building_eiffel_tower)", "Default Production", "pm_default_building_eiffel_tower"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_eiffel_tower
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_eiffel_tower)

Метод производства · `pm_default_building_eiffel_tower` · `common/production_methods/08_monuments.txt:4`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `100`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `100` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_eiffel_tower)|Основа (pmg_base_building_eiffel_tower)]]
