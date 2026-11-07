---
type: concept
description: "Метод производства «Satellite Communications Network» — T&R 1.13, `pm_satellite_communications_network_building_telecommunications`"
project: vic3
audience: agent
source: tr
aliases: ["Satellite Communications Network", "pm_satellite_communications_network_building_telecommunications"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_satellite_communications_network_building_telecommunications
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Satellite Communications Network

Метод производства · `pm_satellite_communications_network_building_telecommunications` · `common/production_methods/ztr_data_production_methods.txt:760`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/satellites_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Telecommunications|Telecommunications]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copperwires_add` = `25` → [[tr/Товары/Wires|Wires]]
    - `goods_input_space_assets_add` = `3` → [[tr/Товары/Space Assets|Space Assets]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_telecommunications_add` = `120` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Telecommunications|Telecommunications]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/No Wireless Network|No Wireless Network]]
