---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_building_oil_rig)» — T&R 1.13, `pm_rail_transport_building_oil_rig`"
project: vic3
source: tr
aliases: ["Перевозка по рельсам (pm_rail_transport_building_oil_rig)", "Перевозка по рельсам", "pm_rail_transport_building_oil_rig"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_building_oil_rig
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_rail_transport_building_oil_rig)]]"
---
# Перевозка по рельсам (pm_rail_transport_building_oil_rig)

Метод производства · `pm_rail_transport_building_oil_rig` · `common/production_methods/ztr_vanilla_production_methods.txt:1864` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
