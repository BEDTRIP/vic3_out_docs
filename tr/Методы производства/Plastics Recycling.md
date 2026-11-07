---
type: concept
description: "Метод производства «Plastics Recycling» — T&R 1.13, `pm_plastic_recycling`"
project: vic3
source: tr
aliases: ["Plastics Recycling", "pm_plastic_recycling"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_plastic_recycling
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Plastics Recycling

Метод производства · `pm_plastic_recycling` · `common/production_methods/ztr_new_production_methods.txt:9275`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/plastic_recycling.dds`
- **unlocking_technologies**: [[tr/Технологии/Plastic Recovery|Plastic Recovery]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_plastics_add` = `2` → [[tr/Товары/Пластмассы|Пластмассы]]
- **disallowing_laws**: [[tr/Законы/No Enviroment Protection|No Enviroment Protection]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Recycling Center|Recycling Center]]
