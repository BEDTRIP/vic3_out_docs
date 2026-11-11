---
type: concept
description: "Метод производства «Timber Tracks» — Gates of Bosphorus 1.15, `pm_gbbf_timber_tracks`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Timber Tracks", "pm_gbbf_timber_tracks"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_timber_tracks
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Timber Tracks

Метод производства · `pm_gbbf_timber_tracks` · `common/production_methods/gbbf_07_government_methods.txt:144`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hardwood_selection.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Механические инструменты|Механические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `5` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `100` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `5`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Mode of Transport|Mode of Transport]]
