---
type: concept
description: "Метод производства «Digital Data On Premises (pm_digital_data_on_premises_heavy_industry_computer)» — T&R 1.13, `pm_digital_data_on_premises_heavy_industry_computer`"
project: vic3
source: tr
aliases: ["Digital Data On Premises (pm_digital_data_on_premises_heavy_industry_computer)", "Digital Data On Premises", "pm_digital_data_on_premises_heavy_industry_computer"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_data_on_premises_heavy_industry_computer
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Digital Data On Premises (pm_digital_data_on_premises_heavy_industry_computer)

Метод производства · `pm_digital_data_on_premises_heavy_industry_computer` · `common/production_methods/ztr_data_production_methods.txt:1555`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_data_on_premises.dds`
- **unlocking_technologies**: [[tr/Технологии/Digital Infrastructure|Digital Infrastructure]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_computer_add` = `-0.5` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `1` → [[tr/Товары/Software|Software]]
    - `goods_input_business_data_add` = `3` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `10` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.65`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_computer)|Optimization (pmg_data_optimization_heavy_industry_computer)]]
