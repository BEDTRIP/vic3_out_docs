---
type: concept
description: "Метод производства «Global Outsourcing Hub» — T&R 1.13, `pm_global_outsourcing_hub`"
project: vic3
audience: agent
source: tr
aliases: ["Global Outsourcing Hub", "pm_global_outsourcing_hub"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_global_outsourcing_hub
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Global Outsourcing Hub

Метод производства · `pm_global_outsourcing_hub` · `common/production_methods/ztr_data_production_methods.txt:439`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_global_outsourcing_hub_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Globalization|Globalization]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_office)|Internet (pm_internet_building_office)]], [[tr/Методы производства/Smartworking|Smartworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `70` → [[tr/Товары/Organized Data|Organized Data]]
    - `goods_input_computer_add` = `1` → [[tr/Товары/Computers|Computers]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `8` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_softwares_add` = `2` → [[tr/Товары/Software|Software]]
    - `goods_output_business_data_add` = `95` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `750` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Service Section|Service Section]]
