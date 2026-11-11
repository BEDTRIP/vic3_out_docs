---
type: concept
description: "Метод производства «Old Summer Palace» — Mandate of Heaven 1.15, `pm_default_building_old_summer_palace`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Old Summer Palace", "pm_default_building_old_summer_palace"]
tags: [mandate_of_heaven, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_old_summer_palace
paths: [for addon/Mandate of Heaven/common/production_methods/moh_monuments.txt]
---
# Old Summer Palace

Метод производства · `pm_default_building_old_summer_palace` · `common/production_methods/moh_monuments.txt:1`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `250`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `500` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `50` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[mandate_of_heaven/Группы методов/Old Summer Palace|Old Summer Palace]]
