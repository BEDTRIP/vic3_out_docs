---
type: concept
description: "Метод производства «Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)» — grey USU 1.13, `pm_flash_freezing_building_whaling_station`"
project: vic3
audience: agent
source: grey_usu
aliases: ["Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)", "Flash Freezing", "pm_flash_freezing_building_whaling_station"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_flash_freezing_building_whaling_station
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/xMoG_USU_trains_misc_resource.txt]
replaces: "[[vanilla/Методы производства/Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)]]"
---
# Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)

Метод производства · `pm_flash_freezing_building_whaling_station` · `common/production_methods/xMoG_USU_trains_misc_resource.txt:197`

## Отличия от ваниль

- **state_modifiers**: добавлено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/flash_refrigerated.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сверхбыстрое замораживание|Сверхбыстрое замораживание]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.03` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `7` → [[grey_usu/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `5` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[grey_usu/Товары/Электричество|Электричество]]
