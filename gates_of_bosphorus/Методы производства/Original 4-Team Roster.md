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
    - `country_bureaucracy_add` = `-100`
    - `country_prestige_add` = `25`
    - `country_chariot_racing_active` = `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_grain_add` = `40` → [[vanilla/Товары/Зерно|Зерно]]
    - `goods_input_wood_add` = `20` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_fabric_add` = `20` → [[vanilla/Товары/Ткань|Ткань]]
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `40` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_laborers_add` = `310` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Racing Roster|Racing Roster]]
