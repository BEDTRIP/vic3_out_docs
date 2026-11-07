---
type: concept
description: "Метод производства «Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)» — grey food 1.13, `pm_refrigerated_storage_building_whaling_station`"
project: vic3
audience: agent
source: grey_food
aliases: ["Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)", "Refrigerated Storage", "pm_refrigerated_storage_building_whaling_station"]
tags: [grey_food, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_storage_building_whaling_station
paths: [grey_add_alot_of_things/grey_food/common/production_methods/mog_ztrains_food_inputs.txt]
replaces: "[[vanilla/Методы производства/Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)]]"
---
# Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)

Метод производства · `pm_refrigerated_storage_building_whaling_station` · `common/production_methods/mog_ztrains_food_inputs.txt:151`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_storage.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пастеризация|Пастеризация]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.01` → [[grey_food/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
