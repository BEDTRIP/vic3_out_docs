---
type: concept
description: "Метод производства «Computerized Research Centers» — T&R 1.13, `pm_computerized_research_center`"
project: vic3
audience: agent
source: tr
aliases: ["Computerized Research Centers", "pm_computerized_research_center"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_computerized_research_center
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Computerized Research Centers

Метод производства · `pm_computerized_research_center` · `common/production_methods/ztr_data_production_methods.txt:31`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_computerized_research_center.dds`
- **unlocking_technologies**: [[tr/Технологии/Machine Learning|Machine Learning]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-add|country_weekly_innovation_add]] = `3.25`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `3` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_manzoni_prints_add` = `3` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_electroniccomponents_add` = `1` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - `goods_input_ai_systems_add` = `1` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_output_business_data_add` = `5` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `150` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `300` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `0.3`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_university)|Основа (pmg_base_building_university)]]
