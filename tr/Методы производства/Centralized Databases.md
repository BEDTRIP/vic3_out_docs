---
type: concept
description: "Метод производства «Centralized Databases» — T&R 1.13, `pm_rudimental_data_networks`"
project: vic3
source: tr
aliases: ["Centralized Databases", "pm_rudimental_data_networks"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rudimental_data_networks
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Centralized Databases

Метод производства · `pm_rudimental_data_networks` · `common/production_methods/ztr_new_production_methods.txt:8000`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_rudimental_data_networks.dds`
- **unlocking_technologies**: [[tr/Технологии/Raw Data Processing|Raw Data Processing]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_bureaucracy_add` = `140`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_tax_capacity_add` = `40`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_telecommunications_add` = `8` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_computer_add` = `4` → [[tr/Товары/Computers|Computers]]
    - `goods_input_paper_add` = `2` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_telephones_add` = `4` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - `goods_output_organized_data_add` = `10` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `350` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_government_administration)|Основа (pmg_base_building_government_administration)]]
