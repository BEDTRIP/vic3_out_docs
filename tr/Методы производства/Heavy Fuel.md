---
type: concept
description: "Метод производства «Heavy Fuel» — T&R 1.13, `pm_automation_HFO_fuel`"
project: vic3
source: tr
aliases: ["Heavy Fuel", "pm_automation_HFO_fuel"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_automation_HFO_fuel
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Heavy Fuel

Метод производства · `pm_automation_HFO_fuel` · `common/production_methods/ztr_energy_production_methods.txt:1098`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_automation_HFO_fuel.dds`
- **unlocking_technologies**: [[tr/Технологии/Vacuum Distillation|Vacuum Distillation]]
- **unlocking_production_methods**: [[tr/Методы производства/Oil-Fired Power Plant (pm_oil-fired_plant_3)|Oil-Fired Power Plant (pm_oil-fired_plant_3)]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `-10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_heavy_fuel_add` = `15` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
    - `goods_input_oil_add` = `-25` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_global_electricity_add` = `5` → [[tr/Товары/National Electricity|National Electricity]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Reactor Refining|Reactor Refining]]
