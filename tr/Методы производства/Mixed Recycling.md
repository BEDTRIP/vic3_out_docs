---
type: concept
description: "Метод производства «Mixed Recycling» — T&R 1.13, `pm_mixed_recycling`"
project: vic3
source: tr
aliases: ["Mixed Recycling", "pm_mixed_recycling"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mixed_recycling
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Mixed Recycling

Метод производства · `pm_mixed_recycling` · `common/production_methods/ztr_new_production_methods.txt:9294`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mixed_recycling.dds`
- **unlocking_technologies**: [[tr/Технологии/Urban Sustainability|Urban Sustainability]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_steel_add` = `1` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_output_aluminium_add` = `1` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_output_paper_add` = `1` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_plastics_add` = `0.5` → [[tr/Товары/Пластмассы|Пластмассы]]
- **disallowing_laws**: [[tr/Законы/No Enviroment Protection|No Enviroment Protection]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Recycling Center|Recycling Center]]
