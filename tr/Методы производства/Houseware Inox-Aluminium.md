---
type: concept
description: "Метод производства «Houseware Inox-Aluminium» — T&R 1.13, `pm_aluminium_inox_houseware`"
project: vic3
source: tr
aliases: ["Houseware Inox-Aluminium", "pm_aluminium_inox_houseware"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_aluminium_inox_houseware
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Houseware Inox-Aluminium

Метод производства · `pm_aluminium_inox_houseware` · `common/production_methods/ztr_new_production_methods.txt:5998`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_aluminium_inox_houseware.dds`
- **unlocking_technologies**: [[tr/Технологии/Wöhler-Deville Process|Wöhler-Deville Process]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `20` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_steel_add` = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_lead_add` = `10` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_glass_add` = `115` → [[vanilla/Товары/Стекло|Стекло]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_glassworks)|Основа (pmg_base_building_glassworks)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Uranium Glass|Uranium Glass]], [[tr/Методы производства/Костяной фарфор|Костяной фарфор]]
