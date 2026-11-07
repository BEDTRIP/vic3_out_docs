---
type: concept
description: "Метод производства «Nuclear ICBMs» — T&R 1.13, `pm_icbms`"
project: vic3
source: tr
aliases: ["Nuclear ICBMs", "pm_icbms"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_icbms
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Nuclear ICBMs

Метод производства · `pm_icbms` · `common/production_methods/ztr_military_production_methods.txt:592`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_icbms.dds`
- **unlocking_technologies**: [[tr/Технологии/ICBMs|ICBMs]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-aeroplanes-add|goods_input_aeroplanes_add]] = `20` → [[tr/Товары/Аэропланы|Аэропланы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-ammunition-add|goods_input_ammunition_add]] = `100` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
    - `goods_input_light_fuel_add` = `200` → [[tr/Товары/Light Fuel|Light Fuel]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-officers-add|building_employment_officers_add]] = `-1000` → [[vanilla/Население/Типы/Офицеры|Офицеры]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-from-army-power-projection-mult|country_prestige_from_army_power_projection_mult]] = `0.05`
- **timed_modifiers**: `pm_offense_defense_readjustment`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Nuclear Equipment Delivery Method|Nuclear Equipment Delivery Method]]
