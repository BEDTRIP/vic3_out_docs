---
type: concept
description: "Метод производства «Digital Art» — T&R 1.13, `pm_digital_art`"
project: vic3
source: tr
aliases: ["Digital Art", "pm_digital_art"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_art
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Digital Art

Метод производства · `pm_digital_art` · `common/production_methods/ztr_new_production_methods.txt:10168`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_art.dds`
- **unlocking_technologies**: [[tr/Технологии/User Interface|User Interface]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_manzoni_prints_add` = `8` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_computer_add` = `3` → [[tr/Товары/Computers|Computers]]
    - `goods_input_softwares_add` = `10` → [[tr/Товары/Software|Software]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_fine_art_add` = `16` → [[vanilla/Товары/Картины|Картины]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerk_add` = `-1000`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_art_academy)|Основа (pmg_base_building_art_academy)]]
