---
type: concept
description: "Метод производства «Rockets» — T&R 1.13, `pm_rocket_building_munition_plant`"
project: vic3
audience: agent
source: tr
aliases: ["Rockets", "pm_rocket_building_munition_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rocket_building_munition_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Rockets

Метод производства · `pm_rocket_building_munition_plant` · `common/production_methods/ztr_military_production_methods.txt:38`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rockets_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Rocketry|Rocketry]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-ammunition-add|goods_output_ammunition_add]] = `35` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Missiles|Missiles]]
