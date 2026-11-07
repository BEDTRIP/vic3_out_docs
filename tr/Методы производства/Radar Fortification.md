---
type: concept
description: "Метод производства «Radar Fortification» — T&R 1.13, `pm_naval_fortification_radar_batteries`"
project: vic3
source: tr
aliases: ["Radar Fortification", "pm_naval_fortification_radar_batteries"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_naval_fortification_radar_batteries
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Radar Fortification

Метод производства · `pm_naval_fortification_radar_batteries` · `common/production_methods/ztr_military_production_methods.txt:661`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_naval_fortification_radar_batteries.dds`
- **unlocking_technologies**: [[tr/Технологии/Radar|Radar]]
- **state_modifiers**:
  - **level_scaled**:
    - `state_fortification_naval_invasion_add` = `700`
    - `state_fortification_naval_battle_mult` = `0.25`
    - `state_fortification_bombardment_resistance_add` = `2500`
    - `state_blockade_resistance_add` = `275`
  - **unscaled**:
    - `state_control_strait_bool` = `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_artillery_add` = `6` → [[vanilla/Товары/Артиллерия|Артиллерия]]
    - `goods_input_ammunition_add` = `8` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
    - `goods_input_steel_add` = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_radios_add` = `4` → [[vanilla/Товары/Радио|Радио]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_soldiers_add` = `700` → [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]]
    - `building_employment_officers_add` = `200` → [[vanilla/Население/Типы/Офицеры|Офицеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Укрепления|Укрепления]]
