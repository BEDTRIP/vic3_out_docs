---
type: concept
description: "Метод производства «Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)» — grey USU 1.13, `pm_refrigerated_storage_building_whaling_station`"
project: vic3
source: grey_usu
aliases: ["Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)", "Refrigerated Storage", "pm_refrigerated_storage_building_whaling_station"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_storage_building_whaling_station
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/xMoG_USU_trains_misc_resource.txt]
replaces: "[[vanilla/Методы производства/Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)]]"
---
# Хранение в холодильнике (pm_refrigerated_storage_building_whaling_station)

Метод производства · `pm_refrigerated_storage_building_whaling_station` · `common/production_methods/xMoG_USU_trains_misc_resource.txt:142`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_storage.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пастеризация|Пастеризация]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `building_food_industry_throughput_add` = `0.01` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `5` → [[grey_usu/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[grey_usu/Товары/Электричество|Электричество]]
