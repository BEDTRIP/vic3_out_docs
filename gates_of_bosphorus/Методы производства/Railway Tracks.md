---
type: concept
description: "Метод производства «Railway Tracks» — Gates of Bosphorus 1.13, `pm_gbbf_railway_tracks`"
project: vic3
source: gates_of_bosphorus
aliases: ["Railway Tracks", "pm_gbbf_railway_tracks"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_railway_tracks
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Railway Tracks

Метод производства · `pm_gbbf_railway_tracks` · `common/production_methods/gbbf_07_government_methods.txt:168`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/gauges_non_standard.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `150` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Mode of Transport|Mode of Transport]]
