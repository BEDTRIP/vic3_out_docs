---
type: concept
description: "Метод производства «HPGR Comminution (pm_hpgr_comminution_advancedores_mine)» — T&R 1.13, `pm_hpgr_comminution_advancedores_mine`"
project: vic3
source: tr
aliases: ["HPGR Comminution (pm_hpgr_comminution_advancedores_mine)", "HPGR Comminution", "pm_hpgr_comminution_advancedores_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hpgr_comminution_advancedores_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# HPGR Comminution (pm_hpgr_comminution_advancedores_mine)

Метод производства · `pm_hpgr_comminution_advancedores_mine` · `common/production_methods/ztr_new_production_methods.txt:8432`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hpgr_comminution.dds`
- **unlocking_technologies**: [[tr/Технологии/HPGR|HPGR]]
- **unlocking_production_methods**: [[tr/Методы производства/Heavy Machineries (pm_heavy_machineries_building_advancedores_mine)|Heavy Machineries (pm_heavy_machineries_building_advancedores_mine)]], [[tr/Методы производства/A&R Operations (pm_autonomous_and_remote_ops_building_advancedores_mine)|A&R Operations (pm_autonomous_and_remote_ops_building_advancedores_mine)]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `30` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_steel_add` = `3` → [[vanilla/Товары/Сталь|Сталь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - `building_throughput_add` = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_advancedores_mine)|Steam Automation (pmg_steam_automation_building_advancedores_mine)]]
