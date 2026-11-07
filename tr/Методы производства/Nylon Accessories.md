---
type: concept
description: "Метод производства «Nylon Accessories» — T&R 1.13, `pm_nylon_accessories`"
project: vic3
source: tr
aliases: ["Nylon Accessories", "pm_nylon_accessories"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nylon_accessories
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Nylon Accessories

Метод производства · `pm_nylon_accessories` · `common/production_methods/ztr_new_production_methods.txt:9977`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_nylon_accessories.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Fibres|Synthetic Fibres]]
- **unlocking_production_methods**: [[tr/Методы производства/Synthetic Fabrics|Synthetic Fabrics]], [[tr/Методы производства/Stretchwear|Stretchwear]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-rubber-add|goods_input_rubber_add]] = `10` → [[vanilla/Товары/Каучук|Каучук]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-silk-add|goods_input_silk_add]] = `35` → [[vanilla/Товары/Шёлк|Шёлк]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-clothes-add|goods_output_clothes_add]] = `-75` → [[tr/Товары/Одежда|Одежда]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-luxury-clothes-add|goods_output_luxury_clothes_add]] = `90` → [[vanilla/Товары/Роскошная одежда|Роскошная одежда]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `750` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство предметов роскоши (pmg_luxury_building_textile_mill)|Производство предметов роскоши (pmg_luxury_building_textile_mill)]]
