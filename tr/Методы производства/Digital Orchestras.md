---
type: concept
description: "Метод производства «Digital Orchestras» — T&R 1.13, `pm_elgar_digital_orchestra`"
project: vic3
audience: agent
source: tr
aliases: ["Digital Orchestras", "pm_elgar_digital_orchestra"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_digital_orchestra
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Digital Orchestras

Метод производства · `pm_elgar_digital_orchestra` · `common/production_methods/ztr_modified_mr_production_methods.txt:220`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_elgar_digital_orchestra.dds`
- **unlocking_technologies**: [[tr/Технологии/Interactive Media|Interactive Media]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_elgar_instruments_add` = `15` → [[tr/Товары/Instruments|Instruments]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_interactive_entertainment_add` = `5` → [[tr/Товары/Interactive Entertainment|Interactive Entertainment]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - `goods_output_elgar_music_add` = `30` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `-50` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Opera Orchestra Size|Opera Orchestra Size]]
