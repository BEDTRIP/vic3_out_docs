---
type: concept
description: "Метод производства «CO2-EOR Storage» — T&R 1.13, `pm_co2_enhanced_oil_recovery`"
project: vic3
source: tr
aliases: ["CO2-EOR Storage", "pm_co2_enhanced_oil_recovery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_co2_enhanced_oil_recovery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# CO2-EOR Storage

Метод производства · `pm_co2_enhanced_oil_recovery` · `common/production_methods/ztr_new_production_methods.txt:7425`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_carbon_capture.dds`
- **unlocking_technologies**: `carbon_capture_storage`
- **unlocking_production_methods**: [[tr/Методы производства/Hydraulic Fracturing|Hydraulic Fracturing]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `-5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `10` → [[tr/Товары/Water|Water]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_oil_add` = `50` → [[vanilla/Товары/ГСМ|ГСМ]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Carbon Capture (pmg_carbon_capture_building_oil_rig)|Carbon Capture (pmg_carbon_capture_building_oil_rig)]]
