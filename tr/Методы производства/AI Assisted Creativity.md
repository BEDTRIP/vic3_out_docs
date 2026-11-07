---
type: concept
description: "Метод производства «AI Assisted Creativity» — T&R 1.13, `pm_ai_assisted_art`"
project: vic3
source: tr
aliases: ["AI Assisted Creativity", "pm_ai_assisted_art"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_ai_assisted_art
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# AI Assisted Creativity

Метод производства · `pm_ai_assisted_art` · `common/production_methods/ztr_new_production_methods.txt:10195`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_ai_assisted_art.dds`
- **unlocking_technologies**: [[tr/Технологии/Generative AI|Generative AI]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `5` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_computer_add` = `3` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-add|goods_output_fine_art_add]] = `14` → [[vanilla/Товары/Картины|Картины]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerk_add` = `-2000`
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `-500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_art_academy)|Основа (pmg_base_building_art_academy)]]
