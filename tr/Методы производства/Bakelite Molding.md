---
type: concept
description: "Метод производства «Bakelite Molding» — T&R 1.13, `pm_bakelite_molding`"
project: vic3
source: tr
aliases: ["Bakelite Molding", "pm_bakelite_molding"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_bakelite_molding
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Bakelite Molding

Метод производства · `pm_bakelite_molding` · `common/production_methods/ztr_new_production_methods.txt:3679`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_bakelite_molding.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Пластмассы|Пластмассы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_coal_add` = `30` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_wood_add` = `25` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_water_add` = `2` → [[tr/Товары/Water|Water]]
    - `goods_output_plastics_add` = `65` → [[tr/Товары/Пластмассы|Пластмассы]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Plastics & Rubber production|Plastics & Rubber production]]
