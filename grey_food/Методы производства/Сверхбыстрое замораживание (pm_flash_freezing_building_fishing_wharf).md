---
type: concept
description: "Метод производства «Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)» — grey food 1.13, `pm_flash_freezing_building_fishing_wharf`"
project: vic3
source: grey_food
aliases: ["Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)", "Flash Freezing", "pm_flash_freezing_building_fishing_wharf"]
tags: [grey_food, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_flash_freezing_building_fishing_wharf
paths: [grey_add_alot_of_things/grey_food/common/production_methods/mog_ztrains_food_inputs.txt]
replaces: "[[vanilla/Методы производства/Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)]]"
---
# Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)

Метод производства · `pm_flash_freezing_building_fishing_wharf` · `common/production_methods/mog_ztrains_food_inputs.txt:122`

## Отличия от ваниль

- **state_modifiers**: добавлено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/flash_refrigerated.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сверхбыстрое замораживание|Сверхбыстрое замораживание]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_food_industry_throughput_add` = `0.03` → [[grey_food/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `7` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_transportation_add` = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
