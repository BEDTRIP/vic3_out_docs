---
type: concept
description: "Метод производства «Antibiotics» — T&R 1.13, `pm_antibiotics_pharmaceuticals`"
project: vic3
audience: agent
source: tr
aliases: ["Antibiotics", "pm_antibiotics_pharmaceuticals"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_antibiotics_pharmaceuticals
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Antibiotics

Метод производства · `pm_antibiotics_pharmaceuticals` · `common/production_methods/ztr_new_production_methods.txt:7141`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_antibiotics_pharmaceuticals.dds`
- **unlocking_technologies**: [[tr/Технологии/Антибиотики|Антибиотики]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `20` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `25` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `20` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_pharmaceuticals_add` = `95` → [[tr/Товары/Фармацевтика|Фармацевтика]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Pharmaceuticals|Pharmaceuticals]]
