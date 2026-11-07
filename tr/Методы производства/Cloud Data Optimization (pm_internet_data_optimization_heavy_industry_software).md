---
type: concept
description: "Метод производства «Cloud Data Optimization (pm_internet_data_optimization_heavy_industry_software)» — T&R 1.13, `pm_internet_data_optimization_heavy_industry_software`"
project: vic3
source: tr
aliases: ["Cloud Data Optimization (pm_internet_data_optimization_heavy_industry_software)", "Cloud Data Optimization", "pm_internet_data_optimization_heavy_industry_software"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_optimization_heavy_industry_software
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Cloud Data Optimization (pm_internet_data_optimization_heavy_industry_software)

Метод производства · `pm_internet_data_optimization_heavy_industry_software` · `common/production_methods/ztr_data_production_methods.txt:1819`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Big Data Analytics|Big Data Analytics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `6` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `16` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `1.8`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `-100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_software)|Optimization (pmg_data_optimization_heavy_industry_software)]]
