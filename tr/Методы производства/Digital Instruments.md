---
type: concept
description: "Метод производства «Digital Instruments» — T&R 1.13, `pm_elgar_digital_instruments`"
project: vic3
audience: agent
source: tr
aliases: ["Digital Instruments", "pm_elgar_digital_instruments"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_digital_instruments
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Digital Instruments

Метод производства · `pm_elgar_digital_instruments` · `common/production_methods/ztr_modified_mr_production_methods.txt:411`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_digital_instruments_pm.dds`
- **unlocking_technologies**: [[tr/Технологии/Global Music|Global Music]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `8` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_alloys_add` = `20` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_processors_add` = `2` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_elgar_instruments_add` = `75` → [[tr/Товары/Instruments|Instruments]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Musical Instruments|Musical Instruments]]
