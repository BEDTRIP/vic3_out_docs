---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_manila_cathedral_ruins)» — ваниль 1.13, `pm_default_building_manila_cathedral_ruins`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартное производство (pm_default_building_manila_cathedral_ruins)", "Default Production", "pm_default_building_manila_cathedral_ruins"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_manila_cathedral_ruins
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_manila_cathedral_ruins)

Метод производства · `pm_default_building_manila_cathedral_ruins` · `common/production_methods/08_monuments.txt:730`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `10`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `50` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_manila_cathedral_ruins)|Основа (pmg_base_building_manila_cathedral_ruins)]]
