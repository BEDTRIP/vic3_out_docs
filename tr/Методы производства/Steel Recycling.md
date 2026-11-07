---
type: concept
description: "Метод производства «Steel Recycling» — T&R 1.13, `pm_steel_recycling`"
project: vic3
source: tr
aliases: ["Steel Recycling", "pm_steel_recycling"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steel_recycling
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Steel Recycling

Метод производства · `pm_steel_recycling` · `common/production_methods/ztr_new_production_methods.txt:9218`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steel_recycling.dds`
- **unlocking_technologies**: [[tr/Технологии/Sponge Iron|Sponge Iron]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-steel-add|goods_output_steel_add]] = `3` → [[vanilla/Товары/Сталь|Сталь]]
- **disallowing_laws**: [[tr/Законы/No Enviroment Protection|No Enviroment Protection]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Recycling Center|Recycling Center]]
