---
type: concept
description: "Метод производства «Original 4-Team Roster» — Gates of Bosphorus 1.13, `pm_gbbf_original_roster`"
project: vic3
source: gates_of_bosphorus
aliases: ["Original 4-Team Roster", "pm_gbbf_original_roster"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_original_roster
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Original 4-Team Roster

Метод производства · `pm_gbbf_original_roster` · `common/production_methods/gbbf_08_monuments_methods.txt:155`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_original_roster.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-add|country_bureaucracy_add]] = `-100`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
    - `country_chariot_racing_active` = `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-grain-add|goods_input_grain_add]] = `40` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `20` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `20` → [[vanilla/Товары/Ткань|Ткань]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `40` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `310` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Racing Roster|Racing Roster]]
