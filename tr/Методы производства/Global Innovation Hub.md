---
type: concept
description: "Метод производства «Global Innovation Hub» — T&R 1.13, `pm_research_center_advanced`"
project: vic3
source: tr
aliases: ["Global Innovation Hub", "pm_research_center_advanced"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_research_center_advanced
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Global Innovation Hub

Метод производства · `pm_research_center_advanced` · `common/production_methods/ztr_unique_buildings_production_methods.txt:171`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_research_center_advanced.dds`
- **unlocking_technologies**: [[tr/Технологии/Machine Learning|Machine Learning]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-add|country_weekly_innovation_add]] = `50`
    - [[vanilla/движок/Модификаторы S#^m-state-education-access-add|state_education_access_add]] = `0.05`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_raw_data_add` = `800` → [[tr/Товары/Raw Data|Raw Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `20` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_manzoni_prints_add` = `10` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_computer_add` = `50` → [[tr/Товары/Computers|Computers]]
    - `goods_input_robotics_add` = `40` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_ai_systems_add` = `100` → [[tr/Товары/AI Systems|AI Systems]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `25000` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `10000` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Research Center Functionality|Research Center Functionality]]
