---
type: concept
description: "Метод производства «Colored Cathode Tube TV» — T&R 1.13, `pm_colored_cathode_tube_televisions`"
project: vic3
source: tr
aliases: ["Colored Cathode Tube TV", "pm_colored_cathode_tube_televisions"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_colored_cathode_tube_televisions
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Colored Cathode Tube TV

Метод производства · `pm_colored_cathode_tube_televisions` · `common/production_methods/ztr_new_production_methods.txt:6237`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_colored_cathode_tube_televisions.dds`
- **unlocking_technologies**: [[tr/Технологии/Color TV|Color TV]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_glass_add` = `5` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_manzoni_prints_add` = `30` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_telecommunications_add` = `25` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_homeappliances_add` = `-20` → [[tr/Товары/Home Appliances|Home Appliances]]
    - `goods_output_televisions_add` = `55` → [[tr/Товары/Televisions|Televisions]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Television Category|Television Category]]
