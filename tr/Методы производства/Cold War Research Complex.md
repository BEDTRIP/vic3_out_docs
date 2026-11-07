---
type: concept
description: "Метод производства «Cold War Research Complex» — T&R 1.13, `pm_research_center_medium`"
project: vic3
audience: agent
source: tr
aliases: ["Cold War Research Complex", "pm_research_center_medium"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_research_center_medium
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Cold War Research Complex

Метод производства · `pm_research_center_medium` · `common/production_methods/ztr_unique_buildings_production_methods.txt:141`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_research_center_medium.dds`
- **unlocking_technologies**: [[tr/Технологии/Funded Research Projects|Funded Research Projects]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-add|country_weekly_innovation_add]] = `25`
    - [[vanilla/движок/Модификаторы S#^m-state-education-access-add|state_education_access_add]] = `0.05`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `300` → [[tr/Товары/Organized Data|Organized Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `50` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_manzoni_prints_add` = `25` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_electroniccomponents_add` = `50` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_robotics_add` = `20` → [[tr/Товары/Robotics|Robotics]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `20000` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `12500` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Research Center Functionality|Research Center Functionality]]
