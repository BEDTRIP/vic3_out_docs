---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_building_oil_rig)» — grey USU 1.13, `pm_rail_transport_building_oil_rig`"
project: vic3
source: grey_usu
aliases: ["Перевозка по рельсам (pm_rail_transport_building_oil_rig)", "Перевозка по рельсам", "pm_rail_transport_building_oil_rig"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_building_oil_rig
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/xMoG_USU_trains_misc_resource.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_rail_transport_building_oil_rig)]]"
---
# Перевозка по рельсам (pm_rail_transport_building_oil_rig)

Метод производства · `pm_rail_transport_building_oil_rig` · `common/production_methods/xMoG_USU_trains_misc_resource.txt:226`

## Отличия от ваниль

- **state_modifiers**: убрано

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `5` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
