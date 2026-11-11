---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_sagrada_familia_cathedral_3)» — ваниль 1.15, `pm_default_building_sagrada_familia_cathedral_3`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартное производство (pm_default_building_sagrada_familia_cathedral_3)", "Default Production", "pm_default_building_sagrada_familia_cathedral_3"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_sagrada_familia_cathedral_3
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_sagrada_familia_cathedral_3)

Метод производства · `pm_default_building_sagrada_familia_cathedral_3` · `common/production_methods/08_monuments.txt:595`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pol-str-mult|interest_group_ig_devout_pol_str_mult]] = `0.1`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `50`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `400` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_sagrada_familia_cathedral_3)|Основа (pmg_base_building_sagrada_familia_cathedral_3)]]
