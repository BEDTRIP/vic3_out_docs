---
type: concept
description: "Метод производства «Data Optimization (pm_internet_data_optimization_heavy_industry_telecommunications)» — T&R 1.13, `pm_internet_data_optimization_heavy_industry_telecommunications`"
project: vic3
source: tr
aliases: ["Data Optimization (pm_internet_data_optimization_heavy_industry_telecommunications)", "Data Optimization", "pm_internet_data_optimization_heavy_industry_telecommunications"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_optimization_heavy_industry_telecommunications
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Data Optimization (pm_internet_data_optimization_heavy_industry_telecommunications)

Метод производства · `pm_internet_data_optimization_heavy_industry_telecommunications` · `common/production_methods/ztr_data_production_methods.txt:1735`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Big Data Analytics|Big Data Analytics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_softwares_add` = `4` → [[tr/Товары/Software|Software]]
    - `goods_output_telecommunications_add` = `-5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `6` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `16` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `1.8`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_telecommunications)|Optimization (pmg_data_optimization_heavy_industry_telecommunications)]]
