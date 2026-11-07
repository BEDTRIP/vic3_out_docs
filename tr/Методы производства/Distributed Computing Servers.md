---
type: concept
description: "Метод производства «Distributed Computing Servers» — T&R 1.13, `pm_late_computer_server_building_datacenter`"
project: vic3
source: tr
aliases: ["Distributed Computing Servers", "pm_late_computer_server_building_datacenter"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_late_computer_server_building_datacenter
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Distributed Computing Servers

Метод производства · `pm_late_computer_server_building_datacenter` · `common/production_methods/ztr_data_production_methods.txt:681`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_late_computer_server.dds`
- **unlocking_technologies**: [[tr/Технологии/Parallel Computing Architectures|Parallel Computing Architectures]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_raw_data_add` = `-60` → [[tr/Товары/Raw Data|Raw Data]]
    - `goods_input_processors_add` = `6` → [[tr/Товары/Processors|Processors]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_datacenter)|Automation (pmg_automation_building_datacenter)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/AGI|AGI]], [[tr/Методы производства/Generative AI Models|Generative AI Models]]
