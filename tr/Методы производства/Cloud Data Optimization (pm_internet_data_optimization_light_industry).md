---
type: concept
description: "Метод производства «Cloud Data Optimization (pm_internet_data_optimization_light_industry)» — T&R 1.13, `pm_internet_data_optimization_light_industry`"
project: vic3
audience: agent
source: tr
aliases: ["Cloud Data Optimization (pm_internet_data_optimization_light_industry)", "Cloud Data Optimization", "pm_internet_data_optimization_light_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_optimization_light_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Cloud Data Optimization (pm_internet_data_optimization_light_industry)

Метод производства · `pm_internet_data_optimization_light_industry` · `common/production_methods/ztr_data_production_methods.txt:1398`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Big Data Analytics|Big Data Analytics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_softwares_add` = `4` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `6` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `12` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `1.5`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `-100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_light_industry)|Optimization (pmg_data_optimization_light_industry)]], [[tr/Группы методов/Optimization (pmg_data_optimization_light_industry_paper)|Optimization (pmg_data_optimization_light_industry_paper)]]
