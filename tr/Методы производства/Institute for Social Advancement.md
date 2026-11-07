---
type: concept
description: "Метод производства «Institute for Social Advancement» — T&R 1.13, `pm_research_center_education`"
project: vic3
audience: agent
source: tr
aliases: ["Institute for Social Advancement", "pm_research_center_education"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_research_center_education
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Institute for Social Advancement

Метод производства · `pm_research_center_education` · `common/production_methods/ztr_unique_buildings_production_methods.txt:202`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/research_education.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Physics|Modern Physics]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-education-access-add|state_education_access_add]] = `0.05`
    - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `0.1`
    - [[vanilla/движок/Модификаторы C#^m-country-society-tech-research-speed-mult|country_society_tech_research_speed_mult]] = `0.15`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-approval-add|interest_group_ig_intelligentsia_approval_add]] = `2`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Research Center Specialization|Research Center Specialization]]
