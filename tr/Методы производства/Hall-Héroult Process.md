---
type: concept
description: "Метод производства «Hall-Héroult Process» — T&R 1.13, `pm_hall_heroult_process`"
project: vic3
source: tr
aliases: ["Hall-Héroult Process", "pm_hall_heroult_process"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hall_heroult_process
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Hall-Héroult Process

Метод производства · `pm_hall_heroult_process` · `common/production_methods/ztr_new_production_methods.txt:5764`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_hall_heroult_process.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[tr/Технологии/Bayer Process|Bayer Process]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_bauxite_add` = `40` → [[tr/Товары/Bauxite|Bauxite]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_input_advancedores_add` = `2` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_alloys_add` = `-15` → [[tr/Товары/Alloys|Alloys]]
    - `goods_output_aluminium_add` = `80` → [[tr/Товары/Aluminium|Aluminium]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aluminium Process|Aluminium Process]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)|Advanced Assembly Lines (pm_advanced_assembly_lines_building_commonalloys_plant)]], [[tr/Методы производства/Robotic Assembly Lines (pm_robotic_building_commonalloys_plant)|Robotic Assembly Lines (pm_robotic_building_commonalloys_plant)]]
