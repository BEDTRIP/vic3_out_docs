---
type: concept
description: "Метод производства «IDE» — T&R 1.13, `pm_integrated_development_environment_building_software_industry`"
project: vic3
audience: agent
source: tr
aliases: ["IDE", "pm_integrated_development_environment_building_software_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_integrated_development_environment_building_software_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# IDE

Метод производства · `pm_integrated_development_environment_building_software_industry` · `common/production_methods/ztr_data_production_methods.txt:87`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_integrated_development_environment_building_software_industry.dds`
- **unlocking_technologies**: [[tr/Технологии/Software Dev Paradigms|Software Dev Paradigms]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `3` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `2` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_computer_add` = `10` → [[tr/Товары/Computers|Computers]]
    - `goods_output_softwares_add` = `75` → [[tr/Товары/Software|Software]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Software Production|Software Production]]
