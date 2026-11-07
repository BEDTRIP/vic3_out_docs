---
type: concept
description: "Метод производства «Linotype» — T&R 1.13, `manzoni_pm_linotype`"
project: vic3
source: tr
aliases: ["Linotype", "manzoni_pm_linotype"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_linotype
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Linotype

Метод производства · `manzoni_pm_linotype` · `common/production_methods/ztr_modified_mr_production_methods.txt:774`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_linotype.dds`
- **unlocking_technologies**: [[tr/Технологии/Linotype|Linotype]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `40` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `15` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_manzoni_prints_add` = `80` → [[tr/Товары/Media Content|Media Content]]
- **unlocking_production_methods**: [[tr/Методы производства/Early Publishing Communication|Early Publishing Communication]], [[tr/Методы производства/Mid Publishing Communication|Mid Publishing Communication]], [[tr/Методы производства/Late Publishing Communication|Late Publishing Communication]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Prints Production|Prints Production]]
