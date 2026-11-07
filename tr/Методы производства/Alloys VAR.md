---
type: concept
description: "Метод производства «Alloys VAR» — T&R 1.13, `pm_vacuum_arc_remelting`"
project: vic3
audience: agent
source: tr
aliases: ["Alloys VAR", "pm_vacuum_arc_remelting"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_vacuum_arc_remelting
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Alloys VAR

Метод производства · `pm_vacuum_arc_remelting` · `common/production_methods/ztr_new_production_methods.txt:5688`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_vacuum_arc_remelting.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Advanced Electric Arc Processes|Advanced Electric Arc Processes]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_advancedores_add` = `15` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_commonores_add` = `55` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_input_gas_add` = `15` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_copper_add` = `20` → [[tr/Товары/Copper|Copper]]
    - `goods_output_alloys_add` = `175` → [[tr/Товары/Alloys|Alloys]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Alloys & Aluminium Process|Alloys & Aluminium Process]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)|Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)]], [[tr/Методы производства/Robotic Assembly Lines (pm_robotic_building_commonalloys_plant)|Robotic Assembly Lines (pm_robotic_building_commonalloys_plant)]]
