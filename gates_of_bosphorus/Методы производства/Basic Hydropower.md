---
type: concept
description: "Метод производства «Basic Hydropower» — Gates of Bosphorus 1.13, `pm_gbbf_basic_hydropower`"
project: vic3
source: gates_of_bosphorus
aliases: ["Basic Hydropower", "pm_gbbf_basic_hydropower"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_basic_hydropower
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Basic Hydropower

Метод производства · `pm_gbbf_basic_hydropower` · `common/production_methods/gbbf_07_government_methods.txt:270`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_basic_hydropower.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Производство электричества|Производство электричества]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_electricity_add` = `50` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `200` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Power Production|Power Production]]
