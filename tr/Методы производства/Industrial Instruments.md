---
type: concept
description: "Метод производства «Industrial Instruments» — T&R 1.13, `pm_elgar_industrial_instruments`"
project: vic3
source: tr
aliases: ["Industrial Instruments", "pm_elgar_industrial_instruments"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_industrial_instruments
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Industrial Instruments

Метод производства · `pm_elgar_industrial_instruments` · `common/production_methods/ztr_modified_mr_production_methods.txt:361`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_industrial_instruments_pm.dds`
- **unlocking_technologies**: [[tr/Технологии/Механические инструменты|Механические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `30` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_elgar_instruments_add` = `45` → [[tr/Товары/Instruments|Instruments]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Musical Instruments|Musical Instruments]]
