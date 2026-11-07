---
type: concept
description: "Метод производства «Photomask Projection» — T&R 1.13, `pm_photomask_projection`"
project: vic3
source: tr
aliases: ["Photomask Projection", "pm_photomask_projection"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_photomask_projection
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Photomask Projection

Метод производства · `pm_photomask_projection` · `common/production_methods/ztr_new_production_methods.txt:470`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_photomask_projection.dds`
- **unlocking_technologies**: [[tr/Технологии/Integrated Circuits|Integrated Circuits]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `3` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[vanilla/Товары/Инструменты|Инструменты]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_chip_foundry)|Automation (pmg_automation_building_chip_foundry)]]
