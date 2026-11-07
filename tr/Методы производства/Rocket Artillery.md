---
type: concept
description: "Метод производства «Rocket Artillery» — T&R 1.13, `pm_mobile_artillery`"
project: vic3
source: tr
aliases: ["Rocket Artillery", "pm_mobile_artillery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mobile_artillery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Rocket Artillery

Метод производства · `pm_mobile_artillery` · `common/production_methods/ztr_new_production_methods.txt:7844`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rocket_artillery.dds`
- **unlocking_technologies**: [[tr/Технологии/Rocket Artillery|Rocket Artillery]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `35` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_alloys_add` = `12` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_lubricant_add` = `5` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-artillery-add|goods_output_artillery_add]] = `110` → [[vanilla/Товары/Артиллерия|Артиллерия]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Литейные|Литейные]]
