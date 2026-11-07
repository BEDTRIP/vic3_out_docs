---
type: concept
description: "Метод производства «Voltaic Pile» — T&R 1.13, `pm_voltaic_pile`"
project: vic3
audience: agent
source: tr
aliases: ["Voltaic Pile", "pm_voltaic_pile"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_voltaic_pile
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Voltaic Pile

Метод производства · `pm_voltaic_pile` · `common/production_methods/ztr_new_production_methods.txt:4332`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/voltaic_pile.dds`
- **unlocking_technologies**: [[tr/Технологии/Electromagnetism|Electromagnetism]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_commonores_add` = `15` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_copper_add` = `10` → [[tr/Товары/Copper|Copper]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-sulfur-add|goods_input_sulfur_add]] = `10` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_batteries_add` = `50` → [[tr/Товары/Batteries|Batteries]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Battery|Battery]]
