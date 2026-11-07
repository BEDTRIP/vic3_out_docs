---
type: concept
description: "Метод производства «Computerized Filing» — T&R 1.13, `pm_local_computer_networks`"
project: vic3
audience: agent
source: tr
aliases: ["Computerized Filing", "pm_local_computer_networks"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_local_computer_networks
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Computerized Filing

Метод производства · `pm_local_computer_networks` · `common/production_methods/ztr_new_production_methods.txt:7965`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_local_computer_networks.dds`
- **unlocking_technologies**: [[tr/Технологии/Networking Protocols|Networking Protocols]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-add|country_bureaucracy_add]] = `120`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `35`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_telecommunications_add` = `4` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `8` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `4` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_softwares_add` = `2` → [[tr/Товары/Software|Software]]
    - `goods_output_organized_data_add` = `5` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `450` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_government_administration)|Основа (pmg_base_building_government_administration)]]
