---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_cristo_redentor)» — ваниль 1.13, `pm_default_building_cristo_redentor`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартное производство (pm_default_building_cristo_redentor)", "Default Production", "pm_default_building_cristo_redentor"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_cristo_redentor
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_cristo_redentor)

Метод производства · `pm_default_building_cristo_redentor` · `common/production_methods/08_monuments.txt:25`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pol-str-mult|interest_group_ig_devout_pol_str_mult]] = `0.15`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `50`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `100` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_cristo_redentor)|Основа (pmg_base_building_cristo_redentor)]]
