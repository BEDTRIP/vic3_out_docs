---
type: concept
description: "Метод производства «Integrated Fortification Grid» — T&R 1.13, `pm_naval_fortification_integrated_defense_grid`"
project: vic3
audience: agent
source: tr
aliases: ["Integrated Fortification Grid", "pm_naval_fortification_integrated_defense_grid"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_naval_fortification_integrated_defense_grid
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Integrated Fortification Grid

Метод производства · `pm_naval_fortification_integrated_defense_grid` · `common/production_methods/ztr_military_production_methods.txt:725`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/network_centric_warfare.dds`
- **unlocking_technologies**: [[tr/Технологии/Network-Centric Warfare|Network-Centric Warfare]]
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-fortification-naval-invasion-add|state_fortification_naval_invasion_add]] = `1000`
    - [[vanilla/движок/Модификаторы S#^m-state-fortification-naval-battle-mult|state_fortification_naval_battle_mult]] = `0.35`
    - [[vanilla/движок/Модификаторы S#^m-state-fortification-bombardment-resistance-add|state_fortification_bombardment_resistance_add]] = `3500`
    - [[vanilla/движок/Модификаторы S#^m-state-blockade-resistance-add|state_blockade_resistance_add]] = `400`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-control-strait-bool|state_control_strait_bool]] = `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-artillery-add|goods_input_artillery_add]] = `6` → [[vanilla/Товары/Артиллерия|Артиллерия]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-ammunition-add|goods_input_ammunition_add]] = `10` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `6` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-radios-add|goods_input_radios_add]] = `4` → [[vanilla/Товары/Радио|Радио]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - `goods_input_robotics_add` = `2` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `8` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-soldiers-add|building_employment_soldiers_add]] = `500` → [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-officers-add|building_employment_officers_add]] = `200` → [[vanilla/Население/Типы/Офицеры|Офицеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Укрепления|Укрепления]]
