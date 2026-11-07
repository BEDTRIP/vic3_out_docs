---
type: concept
description: "Метод производства «Casual Games Development» — T&R 1.13, `pm_cross_platform_building_interactive_media_industry`"
project: vic3
source: tr
aliases: ["Casual Games Development", "pm_cross_platform_building_interactive_media_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cross_platform_building_interactive_media_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Casual Games Development

Метод производства · `pm_cross_platform_building_interactive_media_industry` · `common/production_methods/ztr_data_production_methods.txt:291`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mobile_controller.dds`
- **unlocking_technologies**: [[tr/Технологии/App Economy|App Economy]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_office)|Internet (pm_internet_building_office)]], [[tr/Методы производства/Smartworking|Smartworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_softwares_add` = `30` → [[tr/Товары/Software|Software]]
    - `goods_input_televisions_add` = `10` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_computer_add` = `15` → [[tr/Товары/Computers|Computers]]
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_interactive_entertainment_add` = `120` → [[tr/Товары/Interactive Entertainment|Interactive Entertainment]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `750` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_engineers_add` = `1250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_academics_add` = `750` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Interactive Media Production|Interactive Media Production]]
