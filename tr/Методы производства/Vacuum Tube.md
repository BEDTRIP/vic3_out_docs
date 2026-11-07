---
type: concept
description: "Метод производства «Vacuum Tube» — T&R 1.13, `pm_vacuum_tube`"
project: vic3
audience: agent
source: tr
aliases: ["Vacuum Tube", "pm_vacuum_tube"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_vacuum_tube
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Vacuum Tube

Метод производства · `pm_vacuum_tube` · `common/production_methods/ztr_new_production_methods.txt:4194`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_vacuum_tube.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрические конденсаторы|Электрические конденсаторы]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `25` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-lead-add|goods_input_lead_add]] = `5` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `5` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_output_copperwires_add` = `-25` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electroniccomponents_add` = `50` → [[tr/Товары/Electronic Components|Electronic Components]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Electronic Components|Electronic Components]]
