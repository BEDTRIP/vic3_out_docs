---
type: concept
description: "Метод производства «Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)» — grey food 1.13, `pm_refrigerated_rail_cars_building_livestock_ranch`"
project: vic3
audience: agent
source: grey_food
aliases: ["Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)", "Refrigerated Rail Cars", "pm_refrigerated_rail_cars_building_livestock_ranch"]
tags: [grey_food, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_rail_cars_building_livestock_ranch
paths: [grey_add_alot_of_things/grey_food/common/production_methods/mog_ztrains_food_inputs.txt]
replaces: "[[vanilla/Методы производства/Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)]]"
---
# Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)

Метод производства · `pm_refrigerated_rail_cars_building_livestock_ranch` · `common/production_methods/mog_ztrains_food_inputs.txt:40`

## Отличия от ваниль

- **unlocking_technologies**: изменено
- **state_modifiers**: добавлено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сверхбыстрое замораживание|Сверхбыстрое замораживание]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.02` → [[grey_food/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `2` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
