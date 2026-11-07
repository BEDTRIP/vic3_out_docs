---
type: concept
description: "Метод производства «Internet Data Reporting (pm_internet_data_reporting_light_industry)» — T&R 1.13, `pm_internet_data_reporting_light_industry`"
project: vic3
audience: agent
source: tr
aliases: ["Internet Data Reporting (pm_internet_data_reporting_light_industry)", "Internet Data Reporting", "pm_internet_data_reporting_light_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_reporting_light_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Internet Data Reporting (pm_internet_data_reporting_light_industry)

Метод производства · `pm_internet_data_reporting_light_industry` · `common/production_methods/ztr_data_production_methods.txt:1374`

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
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.85`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `-50` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_light_industry)|Optimization (pmg_data_optimization_light_industry)]], [[tr/Группы методов/Optimization (pmg_data_optimization_light_industry_paper)|Optimization (pmg_data_optimization_light_industry_paper)]]
