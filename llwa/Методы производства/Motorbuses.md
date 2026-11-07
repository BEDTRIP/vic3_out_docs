---
type: concept
description: "Метод производства «Motorbuses» — LLWA 1.13, `LLWA_pm_motor_buses`"
project: vic3
audience: agent
source: llwa
aliases: ["Motorbuses", "LLWA_pm_motor_buses"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_motor_buses
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Motorbuses

Метод производства · `LLWA_pm_motor_buses` · `common/production_methods/LLWA_roads.txt:250`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_motor_buses.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Steam Trucks|Steam Trucks]], [[llwa/Методы производства/Electric Trucks|Electric Trucks]], [[llwa/Методы производства/Petrol Trucks|Petrol Trucks]]
- **unlocking_technologies**: [[vanilla/Технологии/Двигатель внутреннего сгорания|Двигатель внутреннего сгорания]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `2` → [[vanilla/Товары/Автомобили|Автомобили]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `1` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `25` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `200` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `7`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Passenger Buses|Passenger Buses]]
