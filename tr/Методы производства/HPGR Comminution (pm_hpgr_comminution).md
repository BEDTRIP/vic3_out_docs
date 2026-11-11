---
type: concept
description: "Метод производства «HPGR Comminution (pm_hpgr_comminution)» — T&R 1.13, `pm_hpgr_comminution`"
project: vic3
audience: agent
source: tr
aliases: ["HPGR Comminution (pm_hpgr_comminution)", "HPGR Comminution", "pm_hpgr_comminution"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hpgr_comminution
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# HPGR Comminution (pm_hpgr_comminution)

Метод производства · `pm_hpgr_comminution` · `common/production_methods/ztr_new_production_methods.txt:8365`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hpgr_comminution.dds`
- **unlocking_technologies**: [[tr/Технологии/HPGR|HPGR]]
- **unlocking_production_methods**: [[tr/Методы производства/Heavy Machineries (pm_heavy_machineries_building_iron_mine)|Heavy Machineries (pm_heavy_machineries_building_iron_mine)]], [[tr/Методы производства/Heavy Machineries (pm_heavy_machineries_building_copper_mine)|Heavy Machineries (pm_heavy_machineries_building_copper_mine)]], [[tr/Методы производства/Heavy Machineries (pm_heavy_machineries_building_commonores_mine)|Heavy Machineries (pm_heavy_machineries_building_commonores_mine)]], [[tr/Методы производства/Heavy Machineries (pm_heavy_machineries_building_uranium_mine)|Heavy Machineries (pm_heavy_machineries_building_uranium_mine)]], [[tr/Методы производства/A&R Operations (pm_autonomous_and_remote_ops_building_iron_mine)|A&R Operations (pm_autonomous_and_remote_ops_building_iron_mine)]], [[tr/Методы производства/A&R Operations (pm_autonomous_and_remote_ops_building_copper_mine)|A&R Operations (pm_autonomous_and_remote_ops_building_copper_mine)]], [[tr/Методы производства/A&R Operations (pm_autonomous_and_remote_ops_building_commonores_mine)|A&R Operations (pm_autonomous_and_remote_ops_building_commonores_mine)]], [[tr/Методы производства/A&R Operations (pm_autonomous_and_remote_ops_building_uranium_mine)|A&R Operations (pm_autonomous_and_remote_ops_building_uranium_mine)]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `2` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_robotics_add` = `1` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `1` → [[vanilla/Товары/Сталь|Сталь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Steam Automation (pmg_curie_steam_automation_building_uranium_mine)|Steam Automation (pmg_curie_steam_automation_building_uranium_mine)]], [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_commonores_mine)|Steam Automation (pmg_steam_automation_building_commonores_mine)]], [[tr/Группы методов/Паровая автоматизация (pmg_steam_automation_building_copper_mine)|Паровая автоматизация (pmg_steam_automation_building_copper_mine)]], [[tr/Группы методов/Паровая автоматизация (pmg_steam_automation_building_iron_mine)|Паровая автоматизация (pmg_steam_automation_building_iron_mine)]]
