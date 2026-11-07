---
type: concept
description: "Метод производства «Massive Reservoir» — Gates of Bosphorus 1.13, `pm_gbbf_massive_reservior`"
project: vic3
source: gates_of_bosphorus
aliases: ["Massive Reservoir", "pm_gbbf_massive_reservior"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_massive_reservior
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Massive Reservoir

Метод производства · `pm_gbbf_massive_reservior` · `common/production_methods/gbbf_07_government_methods.txt:350`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_massive_reservior.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пневматические инструменты|Пневматические инструменты]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `20`
    - `state_harvest_condition_drought_duration_mult` = `-0.50`
    - `state_harvest_condition_drought_impact_mult` = `-0.50`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_engineers_add` = `200` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Reservoir Size|Reservoir Size]]
