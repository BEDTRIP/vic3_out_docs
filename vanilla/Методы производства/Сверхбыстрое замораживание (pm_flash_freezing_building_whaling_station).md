---
type: concept
description: "Метод производства «Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)» — ваниль 1.13, `pm_flash_freezing_building_whaling_station`"
project: vic3
audience: agent
source: vanilla
aliases: ["Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)", "Flash Freezing", "pm_flash_freezing_building_whaling_station"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_flash_freezing_building_whaling_station
paths: [.vanillaVIC3/common/production_methods/09_misc_resource.txt]
---
# Сверхбыстрое замораживание (pm_flash_freezing_building_whaling_station)

Метод производства · `pm_flash_freezing_building_whaling_station` · `common/production_methods/09_misc_resource.txt:510`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/flash_refrigerated.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сверхбыстрое замораживание|Сверхбыстрое замораживание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `7` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `7` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Охлаждение (pmg_refrigeration_building_whaling_station)|Охлаждение (pmg_refrigeration_building_whaling_station)]]
