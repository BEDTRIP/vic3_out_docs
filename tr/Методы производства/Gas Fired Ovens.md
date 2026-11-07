---
type: concept
description: "Метод производства «Gas Fired Ovens» — T&R 1.13, `pm_gas_fired_ovens`"
project: vic3
source: tr
aliases: ["Gas Fired Ovens", "pm_gas_fired_ovens"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gas_fired_ovens
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Gas Fired Ovens

Метод производства · `pm_gas_fired_ovens` · `common/production_methods/ztr_new_production_methods.txt:640`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_gas_fired_ovens.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_production_methods**: [[vanilla/Методы производства/Кондитерские|Кондитерские]], [[vanilla/Методы производства/Пекарный порошок|Пекарный порошок]], [[tr/Методы производства/Ultra-processed Food|Ultra-processed Food]]
- **unlocking_technologies**: [[tr/Технологии/Basic Appliances|Basic Appliances]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_gas_add` = `3` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_homeappliances_add` = `3` → [[tr/Товары/Home Appliances|Home Appliances]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Автоматизация (pmg_automation_building_food_industry)|Автоматизация (pmg_automation_building_food_industry)]]
