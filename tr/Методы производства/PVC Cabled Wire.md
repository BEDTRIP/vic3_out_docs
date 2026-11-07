---
type: concept
description: "Метод производства «PVC Cabled Wire» — T&R 1.13, `pm_advanced_copperwires`"
project: vic3
audience: agent
source: tr
aliases: ["PVC Cabled Wire", "pm_advanced_copperwires"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_copperwires
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# PVC Cabled Wire

Метод производства · `pm_advanced_copperwires` · `common/production_methods/ztr_new_production_methods.txt:4109`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/advanced_copperwires.dds`
- **unlocking_technologies**: [[tr/Технологии/Polymer-Insulated Wire|Polymer-Insulated Wire]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `40` → [[tr/Товары/Copper|Copper]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-rubber-add|goods_input_rubber_add]] = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_output_copperwires_add` = `85` → [[tr/Товары/Wires|Wires]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
- **ai_value**: `2000`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Wire|Wire]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Embedded Control Circuit|Embedded Control Circuit]]
