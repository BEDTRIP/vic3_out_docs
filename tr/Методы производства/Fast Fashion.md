---
type: concept
description: "Метод производства «Fast Fashion» — T&R 1.13, `pm_fast_fashion`"
project: vic3
source: tr
aliases: ["Fast Fashion", "pm_fast_fashion"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fast_fashion
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Fast Fashion

Метод производства · `pm_fast_fashion` · `common/production_methods/ztr_new_production_methods.txt:10008`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/fast_fashion.dds`
- **unlocking_technologies**: [[tr/Технологии/Polyester Synthesis|Polyester Synthesis]]
- **unlocking_production_methods**: [[tr/Методы производства/Synthetic Fabrics|Synthetic Fabrics]], [[tr/Методы производства/Stretchwear|Stretchwear]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_rubber_add` = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_fertilizer_add` = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_silk_add` = `40` → [[vanilla/Товары/Шёлк|Шёлк]]
    - `goods_output_clothes_add` = `-75` → [[tr/Товары/Одежда|Одежда]]
    - `goods_output_luxury_clothes_add` = `100` → [[vanilla/Товары/Роскошная одежда|Роскошная одежда]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство предметов роскоши (pmg_luxury_building_textile_mill)|Производство предметов роскоши (pmg_luxury_building_textile_mill)]]
