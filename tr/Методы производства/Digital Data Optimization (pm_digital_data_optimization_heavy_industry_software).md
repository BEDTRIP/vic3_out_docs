---
type: concept
description: "Метод производства «Digital Data Optimization (pm_digital_data_optimization_heavy_industry_software)» — T&R 1.13, `pm_digital_data_optimization_heavy_industry_software`"
project: vic3
source: tr
aliases: ["Digital Data Optimization (pm_digital_data_optimization_heavy_industry_software)", "Digital Data Optimization", "pm_digital_data_optimization_heavy_industry_software"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_data_optimization_heavy_industry_software
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Digital Data Optimization (pm_digital_data_optimization_heavy_industry_software)

Метод производства · `pm_digital_data_optimization_heavy_industry_software` · `common/production_methods/ztr_data_production_methods.txt:1758`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Computers|Computers]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_computer_add` = `0.5` → [[tr/Товары/Computers|Computers]]
    - `goods_input_business_data_add` = `3` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_organized_data_add` = `3` → [[tr/Товары/Organized Data|Organized Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.25`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_software)|Optimization (pmg_data_optimization_heavy_industry_software)]]
