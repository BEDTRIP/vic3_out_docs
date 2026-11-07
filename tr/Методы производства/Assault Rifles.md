---
type: concept
description: "Метод производства «Assault Rifles» — T&R 1.13, `pm_assault_rifles`"
project: vic3
audience: agent
source: tr
aliases: ["Assault Rifles", "pm_assault_rifles"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assault_rifles
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Assault Rifles

Метод производства · `pm_assault_rifles` · `common/production_methods/ztr_new_production_methods.txt:10361`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_assault_rifles.dds`
- **unlocking_technologies**: [[tr/Технологии/Assault Rifle|Assault Rifle]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `20` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_aluminium_add` = `10` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_lubricant_add` = `10` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-small-arms-add|goods_output_small_arms_add]] = `140` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство огнестрельного оружия|Производство огнестрельного оружия]]
