---
type: concept
description: "Метод производства «Digital Data Optimization (pm_digital_data_optimization_primary_sector)» — T&R 1.13, `pm_digital_data_optimization_primary_sector`"
project: vic3
source: tr
aliases: ["Digital Data Optimization (pm_digital_data_optimization_primary_sector)", "Digital Data Optimization", "pm_digital_data_optimization_primary_sector"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_data_optimization_primary_sector
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Digital Data Optimization (pm_digital_data_optimization_primary_sector)

Метод производства · `pm_digital_data_optimization_primary_sector` · `common/production_methods/ztr_data_production_methods.txt:1147`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Computers|Computers]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_computer_add` = `0.3` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `0.5` → [[tr/Товары/Software|Software]]
    - `goods_input_business_data_add` = `3` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_organized_data_add` = `1` → [[tr/Товары/Organized Data|Organized Data]]
  - **unscaled**:
    - `building_throughput_add` = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Optimization (pmg_data_optimization_primary_sector_no_shopkeepers)|Data Optimization (pmg_data_optimization_primary_sector_no_shopkeepers)]], [[tr/Группы методов/Optimization (pmg_data_optimization_primary_sector)|Optimization (pmg_data_optimization_primary_sector)]]
