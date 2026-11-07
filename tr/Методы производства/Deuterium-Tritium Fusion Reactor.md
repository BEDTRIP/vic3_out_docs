---
type: concept
description: "Метод производства «Deuterium-Tritium Fusion Reactor» — T&R 1.13, `pm_fusion_reactor`"
project: vic3
audience: agent
source: tr
aliases: ["Deuterium-Tritium Fusion Reactor", "pm_fusion_reactor"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fusion_reactor
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Deuterium-Tritium Fusion Reactor

Метод производства · `pm_fusion_reactor` · `common/production_methods/ztr_energy_production_methods.txt:1403`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_fusion_reactor.dds`
- **unlocking_technologies**: [[tr/Технологии/Nuclear Fusion Reactor|Nuclear Fusion Reactor]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_water_add` = `300` → [[tr/Товары/Water|Water]]
    - `goods_input_electroniccomponents_add` = `150` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_alloys_add` = `100` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_rare_earths_add` = `75` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_input_copperwires_add` = `500` → [[tr/Товары/Wires|Wires]]
    - `goods_output_global_electricity_add` = `5000` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `5000` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `5000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **country_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-mult|goods_input_electricity_mult]] = `-0.1` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-mult|goods_output_electricity_mult]] = `0.1` → [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Fusion Reactor|Fusion Reactor]]
