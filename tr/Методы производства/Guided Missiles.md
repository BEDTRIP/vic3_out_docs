---
type: concept
description: "Метод производства «Guided Missiles» — T&R 1.13, `pm_guided_missiles_building_munition_plant`"
project: vic3
source: tr
aliases: ["Guided Missiles", "pm_guided_missiles_building_munition_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_guided_missiles_building_munition_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# Guided Missiles

Метод производства · `pm_guided_missiles_building_munition_plant` · `common/production_methods/ztr_military_production_methods.txt:61`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/guided_missiles_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Guided Missiles|Guided Missiles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `10` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-ammunition-add|goods_output_ammunition_add]] = `50` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Missiles|Missiles]]
