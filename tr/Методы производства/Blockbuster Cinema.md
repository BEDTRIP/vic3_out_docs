---
type: concept
description: "Метод производства «Blockbuster Cinema» — T&R 1.13, `blockbuster_films`"
project: vic3
source: tr
aliases: ["Blockbuster Cinema", "blockbuster_films"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: blockbuster_films
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Blockbuster Cinema

Метод производства · `blockbuster_films` · `common/production_methods/ztr_new_production_methods.txt:8196`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/blockbuster_cinema.dds`
- **unlocking_technologies**: [[tr/Технологии/Mass Entertainment|Mass Entertainment]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_televisions_add` = `5` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_manzoni_prints_add` = `10` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_groceries_add` = `5` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_furniture_add` = `5` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_output_elgar_music_add` = `35` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Entertainment Type|Entertainment Type]]
