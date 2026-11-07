---
type: concept
description: "Метод производства «Circular Pressure Printing Machine» — T&R 1.13, `manzoni_pm_cylinder_presses`"
project: vic3
source: tr
aliases: ["Circular Pressure Printing Machine", "manzoni_pm_cylinder_presses"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_cylinder_presses
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Circular Pressure Printing Machine

Метод производства · `manzoni_pm_cylinder_presses` · `common/production_methods/ztr_modified_mr_production_methods.txt:727`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_cylinder_press.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Токарный станок|Токарный станок]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `20` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_manzoni_prints_add` = `40` → [[tr/Товары/Media Content|Media Content]]
- **unlocking_production_methods**: [[tr/Методы производства/Early Publishing Communication|Early Publishing Communication]], [[tr/Методы производства/Mid Publishing Communication|Mid Publishing Communication]], [[tr/Методы производства/Late Publishing Communication|Late Publishing Communication]]
