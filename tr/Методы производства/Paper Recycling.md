---
type: concept
description: "Метод производства «Paper Recycling» — T&R 1.13, `pm_paper_recycling`"
project: vic3
source: tr
aliases: ["Paper Recycling", "pm_paper_recycling"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_paper_recycling
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Paper Recycling

Метод производства · `pm_paper_recycling` · `common/production_methods/ztr_new_production_methods.txt:9256`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/paper_recycling.dds`
- **unlocking_technologies**: [[tr/Технологии/Paper Recycling|Paper Recycling]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_paper_add` = `4` → [[vanilla/Товары/Бумага|Бумага]]
- **disallowing_laws**: [[tr/Законы/No Enviroment Protection|No Enviroment Protection]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Recycling Center|Recycling Center]]
