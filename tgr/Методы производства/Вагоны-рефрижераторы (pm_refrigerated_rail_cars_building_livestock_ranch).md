---
type: concept
description: "Метод производства «Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)» — TGR 1.13, `pm_refrigerated_rail_cars_building_livestock_ranch`"
project: vic3
source: tgr
aliases: ["Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)", "Refrigerated Rail Cars", "pm_refrigerated_rail_cars_building_livestock_ranch"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_rail_cars_building_livestock_ranch
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)]]"
---
# Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)

Метод производства · `pm_refrigerated_rail_cars_building_livestock_ranch` · `common/production_methods/TGR_TRADE_automation.txt:885`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрифицированная железная дорога|Электрифицированная железная дорога]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[tgr/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `1` → [[tgr/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[tgr/Товары/Электричество|Электричество]]
