---
type: concept
description: "Метод производства «Silent Cinema» — T&R 1.13, `silent_films`"
project: vic3
source: tr
aliases: ["Silent Cinema", "silent_films"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: silent_films
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Silent Cinema

Метод производства · `silent_films` · `common/production_methods/ztr_new_production_methods.txt:8145`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/silent_films.dds`
- **unlocking_technologies**: [[tr/Технологии/Silent Cinema|Silent Cinema]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_elgar_instruments_add` = `5` → [[tr/Товары/Instruments|Instruments]]
    - `goods_input_electricity_add` = `6` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_manzoni_prints_add` = `3` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_groceries_add` = `5` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_furniture_add` = `5` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_output_elgar_music_add` = `15` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Entertainment Type|Entertainment Type]]
