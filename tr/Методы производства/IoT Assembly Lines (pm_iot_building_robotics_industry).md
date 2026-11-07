---
type: concept
description: "Метод производства «IoT Assembly Lines (pm_iot_building_robotics_industry)» — T&R 1.13, `pm_iot_building_robotics_industry`"
project: vic3
source: tr
aliases: ["IoT Assembly Lines (pm_iot_building_robotics_industry)", "IoT Assembly Lines", "pm_iot_building_robotics_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_iot_building_robotics_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# IoT Assembly Lines (pm_iot_building_robotics_industry)

Метод производства · `pm_iot_building_robotics_industry` · `common/production_methods/ztr_new_production_methods.txt:1922`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_iot_assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/IoT-Driven Manufacturing|IoT-Driven Manufacturing]]
- **unlocking_production_methods**: [[tr/Методы производства/Data Reporting (pm_internet_data_reporting_heavy_industry_no_shopkeepers)|Data Reporting (pm_internet_data_reporting_heavy_industry_no_shopkeepers)]], [[tr/Методы производства/Algorithmic Optimization (pm_internet_data_algorithmic_dispatch_heavy_industry_no_shopkeepers)|Algorithmic Optimization (pm_internet_data_algorithmic_dispatch_heavy_industry_no_shopkeepers)]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_lubricant_add` = `1` → [[tr/Товары/Lubricants|Lubricants]]
  - **unscaled**:
    - `building_throughput_add` = `0.1`
  - **level_scaled**:
    - `building_employment_machinists_add` = `-1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `-500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_robotics_industry)|Automation (pmg_automation_building_robotics_industry)]]
