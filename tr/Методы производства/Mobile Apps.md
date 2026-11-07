---
type: concept
description: "Метод производства «Mobile Apps» — T&R 1.13, `pm_mobile_based_building_software_industry`"
project: vic3
source: tr
aliases: ["Mobile Apps", "pm_mobile_based_building_software_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mobile_based_building_software_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Mobile Apps

Метод производства · `pm_mobile_based_building_software_industry` · `common/production_methods/ztr_data_production_methods.txt:221`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_mobile_based_building_software_industry.dds`
- **unlocking_technologies**: [[tr/Технологии/App Economy|App Economy]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_office)|Internet (pm_internet_building_office)]], [[tr/Методы производства/Smartworking|Smartworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_telephones_add` = `10` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_computer_add` = `-5` → [[tr/Товары/Computers|Computers]]
    - `goods_output_softwares_add` = `-15` → [[tr/Товары/Software|Software]]
    - `goods_output_interactive_entertainment_add` = `15` → [[tr/Товары/Interactive Entertainment|Interactive Entertainment]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `50` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Software Type|Software Type]]
