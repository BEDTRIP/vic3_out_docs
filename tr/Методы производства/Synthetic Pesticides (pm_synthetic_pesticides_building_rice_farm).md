---
type: concept
description: "Метод производства «Synthetic Pesticides (pm_synthetic_pesticides_building_rice_farm)» — T&R 1.13, `pm_synthetic_pesticides_building_rice_farm`"
project: vic3
source: tr
aliases: ["Synthetic Pesticides (pm_synthetic_pesticides_building_rice_farm)", "Synthetic Pesticides", "pm_synthetic_pesticides_building_rice_farm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_synthetic_pesticides_building_rice_farm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Synthetic Pesticides (pm_synthetic_pesticides_building_rice_farm)

Метод производства · `pm_synthetic_pesticides_building_rice_farm` · `common/production_methods/ztr_agriculture_production_methods.txt:117`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_synthetic_pesticides.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Pesticides|Synthetic Pesticides]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `25` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_grain_add` = `170` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `5000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `4000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
