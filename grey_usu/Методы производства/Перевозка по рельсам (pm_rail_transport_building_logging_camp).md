---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_building_logging_camp)» — grey USU 1.13, `pm_rail_transport_building_logging_camp`"
project: vic3
source: grey_usu
aliases: ["Перевозка по рельсам (pm_rail_transport_building_logging_camp)", "Перевозка по рельсам", "pm_rail_transport_building_logging_camp"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_building_logging_camp
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/xMoG_USU_trains_misc_resource.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_rail_transport_building_logging_camp)]]"
---
# Перевозка по рельсам (pm_rail_transport_building_logging_camp)

Метод производства · `pm_rail_transport_building_logging_camp` · `common/production_methods/xMoG_USU_trains_misc_resource.txt:3`

## Отличия от ваниль

- **state_modifiers**: убрано

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `5` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
