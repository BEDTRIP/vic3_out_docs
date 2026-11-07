---
type: concept
description: "Метод производства «Ziegler-Natta Catalysts» — T&R 1.13, `pm_ziegler-natta_catalysts`"
project: vic3
audience: agent
source: tr
aliases: ["Ziegler-Natta Catalysts", "pm_ziegler-natta_catalysts"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_ziegler-natta_catalysts
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Ziegler-Natta Catalysts

Метод производства · `pm_ziegler-natta_catalysts` · `common/production_methods/ztr_new_production_methods.txt:3788`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hdpe.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[tr/Технологии/HDPE|HDPE]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_gas_add` = `20` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_light_fuel_add` = `25` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_plastics_add` = `140` → [[tr/Товары/Пластмассы|Пластмассы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
- **ai_value**: `2000`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Plastics & Rubber production|Plastics & Rubber production]]
