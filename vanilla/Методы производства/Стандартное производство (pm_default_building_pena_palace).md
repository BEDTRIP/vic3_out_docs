---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_pena_palace)» — ваниль 1.13, `pm_default_building_pena_palace`"
project: vic3
source: vanilla
aliases: ["Стандартное производство (pm_default_building_pena_palace)", "Default Production", "pm_default_building_pena_palace"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_pena_palace
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_pena_palace)

Метод производства · `pm_default_building_pena_palace` · `common/production_methods/08_monuments.txt:638`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_legitimacy_headofstate_add` = `5`
    - `country_prestige_add` = `25`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_aristocrats_add` = `100` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_bureaucrats_add` = `200` → [[vanilla/Население/Типы/Чиновники|Чиновники]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_pena_palace)|Основа (pmg_base_building_pena_palace)]]
