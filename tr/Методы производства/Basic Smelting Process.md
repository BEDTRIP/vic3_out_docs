---
type: concept
description: "Метод производства «Basic Smelting Process» — T&R 1.13, `pm_basic_smelting_process`"
project: vic3
audience: agent
source: tr
aliases: ["Basic Smelting Process", "pm_basic_smelting_process"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_smelting_process
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Basic Smelting Process

Метод производства · `pm_basic_smelting_process` · `common/production_methods/ztr_new_production_methods.txt:5579`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_basic_smelting_process.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Alloyworking|Alloyworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_commonores_add` = `35` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_input_copper_add` = `15` → [[tr/Товары/Медь|Медь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-iron-add|goods_input_iron_add]] = `5` → [[vanilla/Товары/Железо|Железо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `5` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_alloys_add` = `60` → [[tr/Товары/Alloys|Alloys]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Alloys & Aluminium Process|Alloys & Aluminium Process]]
