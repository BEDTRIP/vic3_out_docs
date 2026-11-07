---
type: concept
description: "Метод производства «Modern Refining (pm_purification_mine)» — T&R 1.13, `pm_purification_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Modern Refining (pm_purification_mine)", "Modern Refining", "pm_purification_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_purification_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modern Refining (pm_purification_mine)

Метод производства · `pm_purification_mine` · `common/production_methods/ztr_new_production_methods.txt:8339`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/purification_mine.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Purification|Modern Purification]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `0.5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `2` → [[vanilla/Товары/Удобрение|Удобрение]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Steam Automation (pmg_curie_steam_automation_building_uranium_mine)|Steam Automation (pmg_curie_steam_automation_building_uranium_mine)]], [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_bauxite_mine)|Steam Automation (pmg_steam_automation_building_bauxite_mine)]], [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_commonores_mine)|Steam Automation (pmg_steam_automation_building_commonores_mine)]], [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_copper_mine)|Steam Automation (pmg_steam_automation_building_copper_mine)]], [[tr/Группы методов/Паровая автоматизация (pmg_steam_automation_building_coal_mine)|Паровая автоматизация (pmg_steam_automation_building_coal_mine)]], [[tr/Группы методов/Паровая автоматизация (pmg_steam_automation_building_iron_mine)|Паровая автоматизация (pmg_steam_automation_building_iron_mine)]], [[tr/Группы методов/Паровая автоматизация (pmg_steam_automation_building_lead_mine)|Паровая автоматизация (pmg_steam_automation_building_lead_mine)]], [[tr/Группы методов/Паровая автоматизация (pmg_steam_automation_building_sulfur_mine)|Паровая автоматизация (pmg_steam_automation_building_sulfur_mine)]]
