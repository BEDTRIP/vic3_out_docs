---
type: concept
description: "Метод производства «Steam Buses» — LLWA 1.13, `LLWA_pm_steam_buses`"
project: vic3
source: llwa
aliases: ["Steam Buses", "LLWA_pm_steam_buses"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_steam_buses
paths: [llwa/common/production_methods/LLWA_roads.txt]
---
# Steam Buses

Метод производства · `LLWA_pm_steam_buses` · `common/production_methods/LLWA_roads.txt:190`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_steam_buses.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Steam Trucks|Steam Trucks]], [[llwa/Методы производства/Electric Trucks|Electric Trucks]], [[llwa/Методы производства/Petrol Trucks|Petrol Trucks]]
- **unlocking_technologies**: [[vanilla/Технологии/Молотильные машины|Молотильные машины]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `1` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `100` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Passenger Buses|Passenger Buses]]
