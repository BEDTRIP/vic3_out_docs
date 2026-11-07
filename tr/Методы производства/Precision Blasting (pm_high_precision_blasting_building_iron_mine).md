---
type: concept
description: "Метод производства «Precision Blasting (pm_high_precision_blasting_building_iron_mine)» — T&R 1.13, `pm_high_precision_blasting_building_iron_mine`"
project: vic3
source: tr
aliases: ["Precision Blasting (pm_high_precision_blasting_building_iron_mine)", "Precision Blasting", "pm_high_precision_blasting_building_iron_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_high_precision_blasting_building_iron_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Precision Blasting (pm_high_precision_blasting_building_iron_mine)

Метод производства · `pm_high_precision_blasting_building_iron_mine` · `common/production_methods/ztr_new_production_methods.txt:9797`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/precision_blasting.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[tr/Технологии/Precision Blasting|Precision Blasting]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_explosives_add` = `15` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_iron_add` = `40` → [[vanilla/Товары/Железо|Железо]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Взрывчатка (pmg_explosives_building_iron_mine)|Взрывчатка (pmg_explosives_building_iron_mine)]]
