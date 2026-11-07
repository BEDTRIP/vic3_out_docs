---
type: concept
description: "Метод производства «Nylon» — T&R 1.13, `pm_nylon`"
project: vic3
source: tr
aliases: ["Nylon", "pm_nylon"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nylon
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Nylon

Метод производства · `pm_nylon` · `common/production_methods/ztr_new_production_methods.txt:10045`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/nylon.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Fibres|Synthetic Fibres]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - `goods_input_coal_add` = `3` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_dye_add` = `-10` → [[vanilla/Товары/Красители|Красители]]
    - `goods_output_fertilizer_add` = `-10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_output_silk_add` = `45` → [[vanilla/Товары/Шёлк|Шёлк]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Синтетический краситель|Синтетический краситель]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Синтетический шёлк|Синтетический шёлк]]
