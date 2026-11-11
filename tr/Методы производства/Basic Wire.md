---
type: concept
description: "Метод производства «Basic Wire» — T&R 1.13, `pm_basic_copperwires`"
project: vic3
audience: agent
source: tr
aliases: ["Basic Wire", "pm_basic_copperwires"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_copperwires
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Basic Wire

Метод производства · `pm_basic_copperwires` · `common/production_methods/ztr_new_production_methods.txt:4045`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/basic_copperwires.dds`
- **unlocking_technologies**: [[tr/Технологии/Electromagnetism|Electromagnetism]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `40` → [[tr/Товары/Медь|Медь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_copperwires_add` = `55` → [[tr/Товары/Wires|Wires]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Wire|Wire]]
