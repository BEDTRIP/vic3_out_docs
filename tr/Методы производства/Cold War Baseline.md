---
type: concept
description: "Метод производства «Cold War Baseline» — T&R 1.13, `pm_postwar_base`"
project: vic3
source: tr
aliases: ["Cold War Baseline", "pm_postwar_base"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_postwar_base
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Cold War Baseline

Метод производства · `pm_postwar_base` · `common/production_methods/ztr_unique_buildings_production_methods.txt:35`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refining2.dds`
- **unlocking_technologies**: [[tr/Технологии/Neo-Imperialism|Neo-Imperialism]]
- **state_modifiers**: пусто
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_wood_add` = `300` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_output_water_add` = `300` → [[tr/Товары/Water|Water]]
    - `goods_output_iron_add` = `300` → [[vanilla/Товары/Железо|Железо]]
    - `goods_output_coal_add` = `300` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_sulfur_add` = `300` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_bauxite_add` = `300` → [[tr/Товары/Bauxite|Bauxite]]
    - `goods_output_lead_add` = `300` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_output_copper_add` = `300` → [[tr/Товары/Copper|Copper]]
    - `goods_output_commonores_add` = `300` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_output_advancedores_add` = `300` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_output_tools_add` = `300` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_paper_add` = `300` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_light_fuel_add` = `300` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_oil_add` = `300` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_gas_add` = `300` → [[tr/Товары/Natural Gas|Natural Gas]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `10000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Modern State Baseline|Modern State Baseline]]
