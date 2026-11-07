---
type: concept
description: "Метод производства «Nuclear Bomber» — T&R 1.13, `pm_nuclear_bomber`"
project: vic3
audience: agent
source: tr
aliases: ["Nuclear Bomber", "pm_nuclear_bomber"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nuclear_bomber
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Nuclear Bomber

Метод производства · `pm_nuclear_bomber` · `common/production_methods/ztr_military_production_methods.txt:575`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_bomber.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-aeroplanes-add|goods_input_aeroplanes_add]] = `20` → [[tr/Товары/Аэропланы|Аэропланы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-ammunition-add|goods_input_ammunition_add]] = `40` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
    - `goods_input_light_fuel_add` = `100` → [[tr/Товары/Light Fuel|Light Fuel]]
- **timed_modifiers**: `pm_offense_defense_readjustment`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Nuclear Equipment Delivery Method|Nuclear Equipment Delivery Method]]
