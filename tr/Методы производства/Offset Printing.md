---
type: concept
description: "Метод производства «Offset Printing» — T&R 1.13, `pm_offset_printing`"
project: vic3
source: tr
aliases: ["Offset Printing", "pm_offset_printing"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_offset_printing
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Offset Printing

Метод производства · `pm_offset_printing` · `common/production_methods/ztr_new_production_methods.txt:9402`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_offset_printing.dds`
- **unlocking_technologies**: [[tr/Технологии/Offset Printing|Offset Printing]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_paper_add` = `50` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_rubber_add` = `10` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_dye_add` = `20` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_manzoni_prints_add` = `100` → [[tr/Товары/Media Content|Media Content]]
- **unlocking_production_methods**: [[tr/Методы производства/Early Publishing Communication|Early Publishing Communication]], [[tr/Методы производства/Mid Publishing Communication|Mid Publishing Communication]], [[tr/Методы производства/Late Publishing Communication|Late Publishing Communication]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Prints Production|Prints Production]]
