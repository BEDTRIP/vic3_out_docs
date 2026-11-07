---
type: concept
description: "Метод производства «Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)» — TGR 1.13, `pm_refrigerated_rail_cars_building_fishing_wharf`"
project: vic3
audience: agent
source: tgr
aliases: ["Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)", "Refrigerated Rail Cars", "pm_refrigerated_rail_cars_building_fishing_wharf"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_rail_cars_building_fishing_wharf
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)]]"
---
# Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_fishing_wharf)

Метод производства · `pm_refrigerated_rail_cars_building_fishing_wharf` · `common/production_methods/TGR_TRADE_automation.txt:929`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Электрифицированная железная дорога|Электрифицированная железная дорога]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[tgr/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `1` → [[tgr/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[tgr/Товары/Электричество|Электричество]]
