---
type: concept
description: "Метод производства «Data Reporting (pm_internet_data_reporting_light_industry_no_shopkeepers)» — T&R 1.13, `pm_internet_data_reporting_light_industry_no_shopkeepers`"
project: vic3
source: tr
aliases: ["Data Reporting (pm_internet_data_reporting_light_industry_no_shopkeepers)", "Data Reporting", "pm_internet_data_reporting_light_industry_no_shopkeepers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_reporting_light_industry_no_shopkeepers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Data Reporting (pm_internet_data_reporting_light_industry_no_shopkeepers)

Метод производства · `pm_internet_data_reporting_light_industry_no_shopkeepers` · `common/production_methods/ztr_data_production_methods.txt:1423`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_reporting.dds`
- **unlocking_technologies**: [[tr/Технологии/Internet|Internet]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_softwares_add` = `3` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `2` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `4` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `10` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - `building_throughput_add` = `0.85`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Optimization (pmg_data_optimization_light_industry_no_shopkeepers)|Data Optimization (pmg_data_optimization_light_industry_no_shopkeepers)]]
