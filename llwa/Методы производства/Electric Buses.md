---
type: concept
description: "Метод производства «Electric Buses» — LLWA 1.13, `LLWA_pm_electric_buses`"
project: vic3
audience: agent
source: llwa
aliases: ["Electric Buses", "LLWA_pm_electric_buses"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_electric_buses
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Electric Buses

Метод производства · `LLWA_pm_electric_buses` · `common/production_methods/LLWA_roads.txt:222`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_electric_buses.dds`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
- **unlocking_production_methods**: [[llwa/Методы производства/Steam Trucks|Steam Trucks]], [[llwa/Методы производства/Electric Trucks|Electric Trucks]], [[llwa/Методы производства/Petrol Trucks|Petrol Trucks]]
- **unlocking_technologies**: [[vanilla/Технологии/Электрические конденсаторы|Электрические конденсаторы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `150` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Passenger Buses|Passenger Buses]]
