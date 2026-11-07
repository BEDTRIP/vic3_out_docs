---
type: concept
description: "Метод производства «Neoclassical Plays» — T&R 1.13, `classic_plays_pm`"
project: vic3
source: tr
aliases: ["Neoclassical Plays", "classic_plays_pm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: classic_plays_pm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Neoclassical Plays

Метод производства · `classic_plays_pm` · `common/production_methods/ztr_new_production_methods.txt:8095`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_theatre_neoclassical_plays.dds`
- **unlocking_technologies**: [[tr/Технологии/Classicism|Classicism]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_elgar_instruments_add` = `10` → [[tr/Товары/Instruments|Instruments]]
    - `goods_input_clothes_add` = `5` → [[tr/Товары/Одежда|Одежда]]
    - `goods_input_luxury_clothes_add` = `5` → [[vanilla/Товары/Роскошная одежда|Роскошная одежда]]
    - `goods_input_groceries_add` = `5` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_furniture_add` = `5` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_output_elgar_music_add` = `20` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `400` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Entertainment Type|Entertainment Type]]
