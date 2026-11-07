---
type: concept
description: "Метод производства «Teleprinter Network» — T&R 1.13, `pm_teleprinter_network_building_office`"
project: vic3
audience: agent
source: tr
aliases: ["Teleprinter Network", "pm_teleprinter_network_building_office"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_teleprinter_network_building_office
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Teleprinter Network

Метод производства · `pm_teleprinter_network_building_office` · `common/production_methods/ztr_data_production_methods.txt:479`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_teleprinter_network_building_office.dds`
- **unlocking_technologies**: [[tr/Технологии/Secure Market Transactions|Secure Market Transactions]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electroniccomponents_add` = `1` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_telecommunications_add` = `2` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `-200` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Transportation (pmg_data_transportation_building_office)|Data Transportation (pmg_data_transportation_building_office)]]
