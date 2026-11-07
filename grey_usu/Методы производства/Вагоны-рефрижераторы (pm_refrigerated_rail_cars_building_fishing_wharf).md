---
type: concept
description: "Метод производства «Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)» — grey USU 1.13, `pm_refrigerated_rail_cars_building_fishing_wharf`"
project: vic3
source: grey_usu
aliases: ["Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)", "Refrigerated Rail Cars", "pm_refrigerated_rail_cars_building_fishing_wharf"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_rail_cars_building_fishing_wharf
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/xMoG_USU_trains_misc_resource.txt]
replaces: "[[vanilla/Методы производства/Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)]]"
---
# Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)

Метод производства · `pm_refrigerated_rail_cars_building_fishing_wharf` · `common/production_methods/xMoG_USU_trains_misc_resource.txt:85`

## Отличия от ваниль

- **state_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`
- **unlocking_technologies**: [[grey_usu/Технологии/Электрифицированная железная дорога|Электрифицированная железная дорога]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.02` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[grey_usu/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `5` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[grey_usu/Товары/Электричество|Электричество]]
