---
type: concept
description: "Метод производства «Digital Administration» — T&R 1.13, `pm_advanced_data_networks`"
project: vic3
source: tr
aliases: ["Digital Administration", "pm_advanced_data_networks"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_data_networks
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Digital Administration

Метод производства · `pm_advanced_data_networks` · `common/production_methods/ztr_new_production_methods.txt:8035`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_data_networks.dds`
- **unlocking_technologies**: [[tr/Технологии/Digital Governance|Digital Governance]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_bureaucracy_add` = `150`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_tax_capacity_add` = `40`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_telecommunications_add` = `12` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_computer_add` = `4` → [[tr/Товары/Computers|Computers]]
    - `goods_input_telephones_add` = `4` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_softwares_add` = `8` → [[tr/Товары/Software|Software]]
    - `goods_output_raw_data_add` = `25` → [[tr/Товары/Raw Data|Raw Data]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_government_administration)|Основа (pmg_base_building_government_administration)]]
