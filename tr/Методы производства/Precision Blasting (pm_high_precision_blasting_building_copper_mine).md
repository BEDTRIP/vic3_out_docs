---
type: concept
description: "Метод производства «Precision Blasting (pm_high_precision_blasting_building_copper_mine)» — T&R 1.13, `pm_high_precision_blasting_building_copper_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Precision Blasting (pm_high_precision_blasting_building_copper_mine)", "Precision Blasting", "pm_high_precision_blasting_building_copper_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_high_precision_blasting_building_copper_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Precision Blasting (pm_high_precision_blasting_building_copper_mine)

Метод производства · `pm_high_precision_blasting_building_copper_mine` · `common/production_methods/ztr_new_production_methods.txt:9657`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/precision_blasting.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Precision Blasting|Precision Blasting]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `15` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_copper_add` = `40` → [[tr/Товары/Copper|Copper]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Explosives (pmg_explosives_building_copper_mine)|Explosives (pmg_explosives_building_copper_mine)]]
