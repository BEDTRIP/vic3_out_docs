---
type: concept
description: "Метод производства «PEM Fuel Cell» — T&R 1.13, `pm_pem_fuel_cell`"
project: vic3
source: tr
aliases: ["PEM Fuel Cell", "pm_pem_fuel_cell"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_pem_fuel_cell
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# PEM Fuel Cell

Метод производства · `pm_pem_fuel_cell` · `common/production_methods/ztr_new_production_methods.txt:4506`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_pem_fuel_cell.dds`
- **unlocking_technologies**: [[tr/Технологии/Electric Vehicles|Electric Vehicles]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_gas_add` = `15` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_water_add` = `15` → [[tr/Товары/Water|Water]]
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_batteries_add` = `50` → [[tr/Товары/Batteries|Batteries]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Fuel Cell|Fuel Cell]]
