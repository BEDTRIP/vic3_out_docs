---
type: concept
description: "Метод производства «Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)» — ваниль 1.13, `pm_refrigerated_rail_cars_building_livestock_ranch`"
project: vic3
source: vanilla
aliases: ["Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)", "Refrigerated Rail Cars", "pm_refrigerated_rail_cars_building_livestock_ranch"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_rail_cars_building_livestock_ranch
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Вагоны-рефрижераторы (pm_refrigerated_rail_cars_building_livestock_ranch)

Метод производства · `pm_refrigerated_rail_cars_building_livestock_ranch` · `common/production_methods/02_agro.txt:650`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрифицированная железная дорога|Электрифицированная железная дорога]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_transportation_add` = `1` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Охлаждение (pmg_refrigeration_building_livestock_ranch)|Охлаждение (pmg_refrigeration_building_livestock_ranch)]]
