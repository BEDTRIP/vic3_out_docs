---
type: concept
description: "Метод производства «Co-bots» — T&R 1.13, `pm_cobots`"
project: vic3
audience: agent
source: tr
aliases: ["Co-bots", "pm_cobots"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cobots
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Co-bots

Метод производства · `pm_cobots` · `common/production_methods/ztr_new_production_methods.txt:4805`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/cobots.dds`
- **unlocking_technologies**: [[tr/Технологии/Co-bots|Co-bots]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `55` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_processors_add` = `10` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-rubber-add|goods_input_rubber_add]] = `10` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_computer_add` = `10` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `10` → [[tr/Товары/Software|Software]]
    - `goods_input_ai_systems_add` = `10` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_output_robotics_add` = `120` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `750` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Robotics|Robotics]]
