---
type: concept
description: "Метод производства «Modern Theatre» — T&R 1.13, `modern_productions_pm`"
project: vic3
audience: agent
source: tr
aliases: ["Modern Theatre", "modern_productions_pm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: modern_productions_pm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modern Theatre

Метод производства · `modern_productions_pm` · `common/production_methods/ztr_new_production_methods.txt:8120`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_theatre_modern_plays.dds`
- **unlocking_technologies**: [[tr/Технологии/Mass Culture|Mass Culture]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-radios-add|goods_input_radios_add]] = `5` → [[vanilla/Товары/Радио|Радио]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-clothes-add|goods_input_clothes_add]] = `5` → [[tr/Товары/Одежда|Одежда]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-luxury-clothes-add|goods_input_luxury_clothes_add]] = `10` → [[vanilla/Товары/Роскошная одежда|Роскошная одежда]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-groceries-add|goods_input_groceries_add]] = `5` → [[vanilla/Товары/Продукты|Продукты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-furniture-add|goods_input_furniture_add]] = `5` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_output_elgar_music_add` = `25` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `400` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Entertainment Type|Entertainment Type]]
