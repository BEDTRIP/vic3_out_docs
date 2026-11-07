---
type: concept
description: "Метод производства «Passenger Flights» — LLWA 1.13, `LLWA_pm_air_travel`"
project: vic3
source: llwa
aliases: ["Passenger Flights", "LLWA_pm_air_travel"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_air_travel
paths: [llwa/common/production_methods/LLWA_air.txt]
---
# Passenger Flights

Метод производства · `LLWA_pm_air_travel` · `common/production_methods/LLWA_air.txt:91`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_air_fare.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Дирижабли|Дирижабли]], [[llwa/Методы производства/Аэропланы|Аэропланы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-luxury-furniture-add|goods_input_luxury_furniture_add]] = `10` → [[vanilla/Товары/Роскошная мебель|Роскошная мебель]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `50` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `5`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Airline Focus|Airline Focus]]
