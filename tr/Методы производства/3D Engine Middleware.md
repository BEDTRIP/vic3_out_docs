---
type: concept
description: "Метод производства «3D Engine Middleware» — T&R 1.13, `pm_3d_engine_building_interactive_media_industry`"
project: vic3
audience: agent
source: tr
aliases: ["3D Engine Middleware", "pm_3d_engine_building_interactive_media_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_3d_engine_building_interactive_media_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# 3D Engine Middleware

Метод производства · `pm_3d_engine_building_interactive_media_industry` · `common/production_methods/ztr_data_production_methods.txt:268`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/new_controller.dds`
- **unlocking_technologies**: [[tr/Технологии/Interactive Media|Interactive Media]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_softwares_add` = `25` → [[tr/Товары/Software|Software]]
    - `goods_input_computer_add` = `10` → [[tr/Товары/Computers|Computers]]
    - `goods_input_televisions_add` = `10` → [[tr/Товары/Televisions|Televisions]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `7` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_interactive_entertainment_add` = `95` → [[tr/Товары/Interactive Entertainment|Interactive Entertainment]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1000` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `750` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Interactive Media Production|Interactive Media Production]]
