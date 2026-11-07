---
type: concept
description: "Метод производства «Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)» — grey food 1.13, `pm_refrigerated_rail_cars_building_fishing_wharf`"
project: vic3
source: grey_food
aliases: ["Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)", "Refrigerated Rail Cars", "pm_refrigerated_rail_cars_building_fishing_wharf"]
tags: [grey_food, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_rail_cars_building_fishing_wharf
paths: [grey_add_alot_of_things/grey_food/common/production_methods/mog_ztrains_food_inputs.txt]
replaces: "[[vanilla/Методы производства/Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)]]"
---
# Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)

Метод производства · `pm_refrigerated_rail_cars_building_fishing_wharf` · `common/production_methods/mog_ztrains_food_inputs.txt:94`

## Отличия от ваниль

- **state_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрифицированная железная дорога|Электрифицированная железная дорога]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_food_industry_throughput_add` = `0.02` → [[grey_food/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_transportation_add` = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
