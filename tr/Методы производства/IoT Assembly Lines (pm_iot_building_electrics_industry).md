---
type: concept
description: "Метод производства «IoT Assembly Lines (pm_iot_building_electrics_industry)» — T&R 1.13, `pm_iot_building_electrics_industry`"
project: vic3
source: tr
aliases: ["IoT Assembly Lines (pm_iot_building_electrics_industry)", "IoT Assembly Lines", "pm_iot_building_electrics_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_iot_building_electrics_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# IoT Assembly Lines (pm_iot_building_electrics_industry)

Метод производства · `pm_iot_building_electrics_industry` · `common/production_methods/ztr_new_production_methods.txt:1501`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_iot_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/IoT-Driven Manufacturing|IoT-Driven Manufacturing]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet Data Reporting (pm_internet_data_reporting_heavy_industry)|Internet Data Reporting (pm_internet_data_reporting_heavy_industry)]], [[tr/Методы производства/Cloud Data Optimization (pm_internet_data_optimization_heavy_industry)|Cloud Data Optimization (pm_internet_data_optimization_heavy_industry)]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_processors_add` = `1` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_lubricant_add` = `1` → [[tr/Товары/Lubricants|Lubricants]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.1`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-1750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_electrics_industry)|Automation (pmg_automation_building_electrics_industry)]]
