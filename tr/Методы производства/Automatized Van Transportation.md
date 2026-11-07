---
type: concept
description: "Метод производства «Automatized Van Transportation» — T&R 1.13, `pm_autonomous_truck_van_transportation`"
project: vic3
source: tr
aliases: ["Automatized Van Transportation", "pm_autonomous_truck_van_transportation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_autonomous_truck_van_transportation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Automatized Van Transportation

Метод производства · `pm_autonomous_truck_van_transportation` · `common/production_methods/ztr_data_production_methods.txt:1082`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_autonomous_truck_transportation.dds`
- **unlocking_technologies**: [[tr/Технологии/Autonomous Road Vehicles|Autonomous Road Vehicles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_automobiles_add` = `3` → [[tr/Товары/Автомобили|Автомобили]]
    - `goods_input_ai_systems_add` = `3` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_telecommunications_add` = `4` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_transportation_add` = `12` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `-500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_transport_building_ecommerce_logistics)|Transport (pmg_transport_building_ecommerce_logistics)]]
