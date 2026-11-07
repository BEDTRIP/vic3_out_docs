---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_steam_rail_transport)» — grey USU 1.13, `pm_steam_rail_transport`"
project: vic3
audience: agent
source: grey_usu
aliases: ["Перевозка по рельсам (pm_steam_rail_transport)", "Rail Transportation", "pm_steam_rail_transport"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_rail_transport
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_trains_plantations.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_steam_rail_transport)]]"
---
# Перевозка по рельсам (pm_steam_rail_transport)

Метод производства · `pm_steam_rail_transport` · `common/production_methods/yMoG_USU_trains_plantations.txt:1`

## Отличия от ваниль

- **building_modifiers**: изменено
- **state_modifiers**: убрано

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `4` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
