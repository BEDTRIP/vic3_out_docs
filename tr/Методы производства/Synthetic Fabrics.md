---
type: concept
description: "Метод производства «Synthetic Fabrics» — T&R 1.13, `pm_synthetic_fabric`"
project: vic3
source: tr
aliases: ["Synthetic Fabrics", "pm_synthetic_fabric"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_synthetic_fabric
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Synthetic Fabrics

Метод производства · `pm_synthetic_fabric` · `common/production_methods/ztr_new_production_methods.txt:9903`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_synthetic_fabric.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Fibres|Synthetic Fibres]]
- **unlocking_production_methods**: [[vanilla/Методы производства/Механизированные ткацкие станки|Механизированные ткацкие станки]], [[tr/Методы производства/Автоматические механические ткацкие станки|Автоматические механические ткацкие станки]], [[tr/Методы производства/CNC Weaving Machines|CNC Weaving Machines]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `40` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-dye-add|goods_input_dye_add]] = `20` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_water_add` = `4` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-clothes-add|goods_output_clothes_add]] = `155` → [[tr/Товары/Одежда|Одежда]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_textile_mill)|Основа (pmg_base_building_textile_mill)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Fast Fashion|Fast Fashion]], [[tr/Методы производства/Nylon Accessories|Nylon Accessories]], [[tr/Методы производства/Эластичные волокна|Эластичные волокна]]
