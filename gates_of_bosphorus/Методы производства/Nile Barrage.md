---
type: concept
description: "Метод производства «Nile Barrage» — Gates of Bosphorus 1.13, `pm_gbbf_nile_barrage`"
project: vic3
source: gates_of_bosphorus
aliases: ["Nile Barrage", "pm_gbbf_nile_barrage"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_nile_barrage
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Nile Barrage

Метод производства · `pm_gbbf_nile_barrage` · `common/production_methods/gbbf_07_government_methods.txt:246`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_nile_barrage.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-flood-impact-mult|state_harvest_condition_flood_impact_mult]] = `-0.75`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-flood-duration-mult|state_harvest_condition_flood_duration_mult]] = `-0.75`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `900` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Nile Barrage|Nile Barrage]]
