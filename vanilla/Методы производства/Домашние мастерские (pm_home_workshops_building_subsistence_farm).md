---
type: concept
description: "Метод производства «Домашние мастерские (pm_home_workshops_building_subsistence_farm)» — ваниль 1.13, `pm_home_workshops_building_subsistence_farm`"
project: vic3
source: vanilla
aliases: ["Домашние мастерские (pm_home_workshops_building_subsistence_farm)", "Домашние мастерские", "pm_home_workshops_building_subsistence_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_home_workshops_building_subsistence_farm
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Домашние мастерские (pm_home_workshops_building_subsistence_farm)

Метод производства · `pm_home_workshops_building_subsistence_farm` · `common/production_methods/12_subsistence.txt:33`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/home_workshops.dds`
- **disallowing_laws**: [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-clothes-add|goods_output_clothes_add]] = `0.25` → [[vanilla/Товары/Одежда|Одежда]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-furniture-add|goods_output_furniture_add]] = `0.25` → [[vanilla/Товары/Мебель|Мебель]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-liquor-add|goods_output_liquor_add]] = `0.25` → [[vanilla/Товары/Спирт|Спирт]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Домашние мастерские (pmg_home_workshops_building_subsistence_farm)|Домашние мастерские (pmg_home_workshops_building_subsistence_farm)]]
