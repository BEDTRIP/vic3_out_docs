---
type: concept
description: "Метод производства «Science & Humanities Department» — T&R 1.13, `pm_big_science_and_humanities_department`"
project: vic3
source: tr
aliases: ["Science & Humanities Department", "pm_big_science_and_humanities_department"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_big_science_and_humanities_department
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Science & Humanities Department

Метод производства · `pm_big_science_and_humanities_department` · `common/production_methods/ztr_data_production_methods.txt:2`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_big_science_and_humanities_department.dds`
- **unlocking_technologies**: [[tr/Технологии/Funded Research Projects|Funded Research Projects]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_weekly_innovation_add` = `2.75`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_paper_add` = `4` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_manzoni_prints_add` = `4` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_business_data_add` = `2` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_academics_add` = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pop_qualifications_mult` = `0.25`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_university)|Основа (pmg_base_building_university)]]
