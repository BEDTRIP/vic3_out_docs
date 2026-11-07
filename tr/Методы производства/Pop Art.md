---
type: concept
description: "Метод производства «Pop Art» — T&R 1.13, `pm_pop_art`"
project: vic3
source: tr
aliases: ["Pop Art", "pm_pop_art"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_pop_art
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Pop Art

Метод производства · `pm_pop_art` · `common/production_methods/ztr_new_production_methods.txt:10141`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_pop_art.dds`
- **unlocking_technologies**: [[tr/Технологии/Pop Art|Pop Art]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_manzoni_prints_add` = `8` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_paper_add` = `10` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_fine_art_add` = `12` → [[vanilla/Товары/Картины|Картины]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `-500` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_art_academy)|Основа (pmg_base_building_art_academy)]]
