---
type: concept
description: "Метод производства «Cloud Based DevOps» — T&R 1.13, `pm_cloud_based_devops_building_software_industry`"
project: vic3
source: tr
aliases: ["Cloud Based DevOps", "pm_cloud_based_devops_building_software_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cloud_based_devops_building_software_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Cloud Based DevOps

Метод производства · `pm_cloud_based_devops_building_software_industry` · `common/production_methods/ztr_data_production_methods.txt:139`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_cloud_based_devops_building_software_industry.dds`
- **unlocking_technologies**: [[tr/Технологии/Cloud Computing|Cloud Computing]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_office)|Internet (pm_internet_building_office)]], [[tr/Методы производства/Smartworking|Smartworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `7` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `3` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_computer_add` = `20` → [[tr/Товары/Computers|Computers]]
    - `goods_output_softwares_add` = `125` → [[tr/Товары/Software|Software]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `750` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `750` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Software Production|Software Production]]
