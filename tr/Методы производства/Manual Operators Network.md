---
type: concept
description: "Метод производства «Manual Operators Network» — T&R 1.13, `pm_manual_operators_network_building_telecommunications`"
project: vic3
audience: agent
source: tr
aliases: ["Manual Operators Network", "pm_manual_operators_network_building_telecommunications"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manual_operators_network_building_telecommunications
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Manual Operators Network

Метод производства · `pm_manual_operators_network_building_telecommunications` · `common/production_methods/ztr_data_production_methods.txt:721`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/telephone_switchboards_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Телефон|Телефон]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copperwires_add` = `15` → [[tr/Товары/Wires|Wires]]
    - `goods_output_telecommunications_add` = `60` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Telecommunications|Telecommunications]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/No Wireless Network|No Wireless Network]]
