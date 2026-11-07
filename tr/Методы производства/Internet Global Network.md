---
type: concept
description: "Метод производства «Internet Global Network» — T&R 1.13, `pm_internet_global_network_building_telecommunications`"
project: vic3
source: tr
aliases: ["Internet Global Network", "pm_internet_global_network_building_telecommunications"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_global_network_building_telecommunications
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Internet Global Network

Метод производства · `pm_internet_global_network_building_telecommunications` · `common/production_methods/ztr_data_production_methods.txt:780`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_building_telecom.dds`
- **unlocking_technologies**: [[tr/Технологии/Broadband & Wireless Networks|Broadband & Wireless Networks]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copperwires_add` = `30` → [[tr/Товары/Wires|Wires]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_space_assets_add` = `5` → [[tr/Товары/Space Assets|Space Assets]]
    - `goods_output_telecommunications_add` = `140` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Telecommunications|Telecommunications]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/2G Cellular Network|2G Cellular Network]], [[tr/Методы производства/4G LTE Network|4G LTE Network]], [[tr/Методы производства/5G IoT Network|5G IoT Network]]
