---
type: concept
description: "Метод производства «Data Optimization (pm_internet_data_optimization_heavy_industry_no_shopkeepers)» — T&R 1.13, `pm_internet_data_optimization_heavy_industry_no_shopkeepers`"
project: vic3
audience: agent
source: tr
aliases: ["Data Optimization (pm_internet_data_optimization_heavy_industry_no_shopkeepers)", "Data Optimization", "pm_internet_data_optimization_heavy_industry_no_shopkeepers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_optimization_heavy_industry_no_shopkeepers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Data Optimization (pm_internet_data_optimization_heavy_industry_no_shopkeepers)

Метод производства · `pm_internet_data_optimization_heavy_industry_no_shopkeepers` · `common/production_methods/ztr_data_production_methods.txt:1645`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Big Data Analytics|Big Data Analytics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_softwares_add` = `4` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `6` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `16` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `1.8`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_no_shopkeepers)|Data Optimization (pmg_data_optimization_heavy_industry_no_shopkeepers)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_battery_plant)|IoT Assembly Lines (pm_iot_building_battery_plant)]]
