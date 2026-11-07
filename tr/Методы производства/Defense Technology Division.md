---
type: concept
description: "Метод производства «Defense Technology Division» — T&R 1.13, `pm_research_military_modernization`"
project: vic3
source: tr
aliases: ["Defense Technology Division", "pm_research_military_modernization"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_research_military_modernization
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Defense Technology Division

Метод производства · `pm_research_military_modernization` · `common/production_methods/ztr_unique_buildings_production_methods.txt:221`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_research_military_modernization.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Physics|Modern Physics]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `unit_offense_mult` = `0.1`
    - `unit_defense_mult` = `0.1`
    - `country_military_tech_spread_mult` = `0.05`
    - `country_military_tech_research_speed_mult` = `0.15`
  - **unscaled**:
    - `interest_group_ig_armed_forces_approval_add` = `2`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Research Center Specialization|Research Center Specialization]]
