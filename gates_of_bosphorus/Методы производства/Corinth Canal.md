---
type: concept
description: "Метод производства «Corinth Canal» — Gates of Bosphorus 1.13, `pm_gbbf_corinth_canal`"
project: vic3
source: gates_of_bosphorus
aliases: ["Corinth Canal", "pm_gbbf_corinth_canal"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_corinth_canal
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Corinth Canal

Метод производства · `pm_gbbf_corinth_canal` · `common/production_methods/gbbf_08_monuments_methods.txt:39`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/canals.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `25`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_machinists_add` = `100` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_capitalists_add` = `50` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Corinth Canal|Corinth Canal]]
