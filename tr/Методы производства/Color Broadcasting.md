---
type: concept
description: "Метод производства «Color Broadcasting» — T&R 1.13, `pm_color_broadcasting`"
project: vic3
audience: agent
source: tr
aliases: ["Color Broadcasting", "pm_color_broadcasting"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_color_broadcasting
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Color Broadcasting

Метод производства · `pm_color_broadcasting` · `common/production_methods/ztr_new_production_methods.txt:9504`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_color_broadcasting.dds`
- **unlocking_technologies**: [[tr/Технологии/Color TV|Color TV]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `25` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_copperwires_add` = `20` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-radios-add|goods_input_radios_add]] = `-10` → [[vanilla/Товары/Радио|Радио]]
    - `goods_input_televisions_add` = `15` → [[tr/Товары/Televisions|Televisions]]
    - `goods_output_manzoni_prints_add` = `95` → [[tr/Товары/Media Content|Media Content]]
    - `goods_output_elgar_music_add` = `35` → [[tr/Товары/Entertainment|Entertainment]]
- **unlocking_production_methods**: [[tr/Методы производства/Broadcasting Communication|Broadcasting Communication]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Broadcast Media Production|Broadcast Media Production]]
