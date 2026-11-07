---
type: concept
description: "Метод производства «Websites» — T&R 1.13, `pm_web_based_building_software_industry`"
project: vic3
audience: agent
source: tr
aliases: ["Websites", "pm_web_based_building_software_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_web_based_building_software_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Websites

Метод производства · `pm_web_based_building_software_industry` · `common/production_methods/ztr_data_production_methods.txt:198`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_web_based_building_software_industry.dds`
- **unlocking_technologies**: [[tr/Технологии/Internet|Internet]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_office)|Internet (pm_internet_building_office)]], [[tr/Методы производства/Smartworking|Smartworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_computer_add` = `-5` → [[tr/Товары/Computers|Computers]]
    - `goods_output_softwares_add` = `-10` → [[tr/Товары/Software|Software]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `20` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Software Type|Software Type]]
