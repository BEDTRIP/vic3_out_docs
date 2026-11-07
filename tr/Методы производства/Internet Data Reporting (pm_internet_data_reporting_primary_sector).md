---
type: concept
description: "Метод производства «Internet Data Reporting (pm_internet_data_reporting_primary_sector)» — T&R 1.13, `pm_internet_data_reporting_primary_sector`"
project: vic3
source: tr
aliases: ["Internet Data Reporting (pm_internet_data_reporting_primary_sector)", "Internet Data Reporting", "pm_internet_data_reporting_primary_sector"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_reporting_primary_sector
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Internet Data Reporting (pm_internet_data_reporting_primary_sector)

Метод производства · `pm_internet_data_reporting_primary_sector` · `common/production_methods/ztr_data_production_methods.txt:1187`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_reporting.dds`
- **unlocking_technologies**: [[tr/Технологии/Internet|Internet]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_softwares_add` = `3` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `1` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `4` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `8` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - `building_throughput_add` = `0.65`
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `-250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_primary_sector)|Optimization (pmg_data_optimization_primary_sector)]]
