---
type: concept
description: "Метод производства «Technology Diffusion Bureau» — T&R 1.13, `pm_research_center_tech_spread`"
project: vic3
audience: agent
source: tr
aliases: ["Technology Diffusion Bureau", "pm_research_center_tech_spread"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_research_center_tech_spread
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_unique_buildings_production_methods.txt]
---
# Technology Diffusion Bureau

Метод производства · `pm_research_center_tech_spread` · `common/production_methods/ztr_unique_buildings_production_methods.txt:241`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_global_outsourcing_hub_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Physics|Modern Physics]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-tech-spread-mult|country_tech_spread_mult]] = `0.15`
    - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `0.15`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-approval-add|interest_group_ig_industrialists_approval_add]] = `2`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Research Center Specialization|Research Center Specialization]]
