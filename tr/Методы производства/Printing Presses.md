---
type: concept
description: "Метод производства «Printing Presses» — T&R 1.13, `manzoni_pm_printing_presses`"
project: vic3
source: tr
aliases: ["Printing Presses", "manzoni_pm_printing_presses"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_printing_presses
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Printing Presses

Метод производства · `manzoni_pm_printing_presses` · `common/production_methods/ztr_modified_mr_production_methods.txt:708`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_printing_press.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `15` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_manzoni_prints_add` = `25` → [[tr/Товары/Media Content|Media Content]]
- **unlocking_production_methods**: [[tr/Методы производства/Early Publishing Communication|Early Publishing Communication]], [[tr/Методы производства/Mid Publishing Communication|Mid Publishing Communication]], [[tr/Методы производства/Late Publishing Communication|Late Publishing Communication]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Prints Production|Prints Production]]
