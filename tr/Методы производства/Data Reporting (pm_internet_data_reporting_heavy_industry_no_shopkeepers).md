---
type: concept
description: "Метод производства «Data Reporting (pm_internet_data_reporting_heavy_industry_no_shopkeepers)» — T&R 1.13, `pm_internet_data_reporting_heavy_industry_no_shopkeepers`"
project: vic3
audience: agent
source: tr
aliases: ["Data Reporting (pm_internet_data_reporting_heavy_industry_no_shopkeepers)", "Data Reporting", "pm_internet_data_reporting_heavy_industry_no_shopkeepers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_reporting_heavy_industry_no_shopkeepers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Data Reporting (pm_internet_data_reporting_heavy_industry_no_shopkeepers)

Метод производства · `pm_internet_data_reporting_heavy_industry_no_shopkeepers` · `common/production_methods/ztr_data_production_methods.txt:1624`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_reporting.dds`
- **unlocking_technologies**: [[tr/Технологии/Internet|Internet]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_softwares_add` = `3` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `2` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `4` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `13` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `1.2`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch_no_shopkeepers)|Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch_no_shopkeepers)]], [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_no_shopkeepers)|Data Optimization (pmg_data_optimization_heavy_industry_no_shopkeepers)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_aircraft_industry)|IoT Assembly Lines (pm_iot_building_aircraft_industry)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_battery_plant)|IoT Assembly Lines (pm_iot_building_battery_plant)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_ecommerce_logistics)|IoT Assembly Lines (pm_iot_building_ecommerce_logistics)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_robotics_industry)|IoT Assembly Lines (pm_iot_building_robotics_industry)]]
