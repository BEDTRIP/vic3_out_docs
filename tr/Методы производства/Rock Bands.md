---
type: concept
description: "Метод производства «Rock Bands» — T&R 1.13, `pm_elgar_rock_band`"
project: vic3
audience: agent
source: tr
aliases: ["Rock Bands", "pm_elgar_rock_band"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_rock_band
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Rock Bands

Метод производства · `pm_elgar_rock_band` · `common/production_methods/ztr_modified_mr_production_methods.txt:202`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_rock_band_pm.dds`
- **unlocking_technologies**: [[tr/Технологии/Rock & Roll|Rock & Roll]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_elgar_instruments_add` = `45` → [[tr/Товары/Instruments|Instruments]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_elgar_music_add` = `25` → [[tr/Товары/Entertainment|Entertainment]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-add|goods_output_fine_art_add]] = `3` → [[vanilla/Товары/Картины|Картины]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Opera Orchestra Size|Opera Orchestra Size]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Modern Dance|Modern Dance]]
