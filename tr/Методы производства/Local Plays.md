---
type: concept
description: "Метод производства «Local Plays» — T&R 1.13, `local_plays_pm`"
project: vic3
source: tr
aliases: ["Local Plays", "local_plays_pm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: local_plays_pm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Local Plays

Метод производства · `local_plays_pm` · `common/production_methods/ztr_new_production_methods.txt:8071`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_theatre_local_plays.dds`
- **unlocking_technologies**: [[tr/Технологии/Classicism|Classicism]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_clothes_add` = `5` → [[tr/Товары/Одежда|Одежда]]
    - `goods_input_fabric_add` = `25` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_groceries_add` = `5` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_furniture_add` = `5` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_output_elgar_music_add` = `15` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `400` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Entertainment Type|Entertainment Type]]
