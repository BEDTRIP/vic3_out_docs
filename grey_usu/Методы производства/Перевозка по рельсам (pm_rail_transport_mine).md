---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_mine)» — grey USU 1.13, `pm_rail_transport_mine`"
project: vic3
source: grey_usu
aliases: ["Перевозка по рельсам (pm_rail_transport_mine)", "Перевозка по рельсам", "pm_rail_transport_mine"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_mine
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_trains_mines.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_rail_transport_mine)]]"
---
# Перевозка по рельсам (pm_rail_transport_mine)

Метод производства · `pm_rail_transport_mine` · `common/production_methods/yMoG_USU_trains_mines.txt:1`

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
