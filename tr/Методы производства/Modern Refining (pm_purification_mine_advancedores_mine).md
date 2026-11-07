---
type: concept
description: "Метод производства «Modern Refining (pm_purification_mine_advancedores_mine)» — T&R 1.13, `pm_purification_mine_advancedores_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Modern Refining (pm_purification_mine_advancedores_mine)", "Modern Refining", "pm_purification_mine_advancedores_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_purification_mine_advancedores_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modern Refining (pm_purification_mine_advancedores_mine)

Метод производства · `pm_purification_mine_advancedores_mine` · `common/production_methods/ztr_new_production_methods.txt:8406`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/purification_mine.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Purification|Modern Purification]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `30` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_advancedores_mine)|Steam Automation (pmg_steam_automation_building_advancedores_mine)]]
