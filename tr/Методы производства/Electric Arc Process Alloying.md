---
type: concept
description: "Метод производства «Electric Arc Process Alloying» — T&R 1.13, `pm_electric_arc_process_alloying`"
project: vic3
audience: agent
source: tr
aliases: ["Electric Arc Process Alloying", "pm_electric_arc_process_alloying"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electric_arc_process_alloying
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electric Arc Process Alloying

Метод производства · `pm_electric_arc_process_alloying` · `common/production_methods/ztr_new_production_methods.txt:5614`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electric_arc_process_alloying.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Дуговая плавка|Дуговая плавка]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_commonores_add` = `50` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_input_copper_add` = `25` → [[tr/Товары/Copper|Copper]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-iron-add|goods_input_iron_add]] = `5` → [[vanilla/Товары/Железо|Железо]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `5` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_alloys_add` = `90` → [[tr/Товары/Alloys|Alloys]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Alloys & Aluminium Process|Alloys & Aluminium Process]]
