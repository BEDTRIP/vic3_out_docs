---
type: concept
description: "Метод производства «Adequate Reservoir» — Gates of Bosphorus 1.15, `pm_gbbf_adequate_reservior`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Adequate Reservoir", "pm_gbbf_adequate_reservior"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_adequate_reservior
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Adequate Reservoir

Метод производства · `pm_gbbf_adequate_reservior` · `common/production_methods/gbbf_07_government_methods.txt:328`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_adequate_reservior.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Железобетон|Железобетон]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-drought-duration-mult|state_harvest_condition_drought_duration_mult]] = `-0.25`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-drought-impact-mult|state_harvest_condition_drought_impact_mult]] = `-0.25`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Reservoir Size|Reservoir Size]]
