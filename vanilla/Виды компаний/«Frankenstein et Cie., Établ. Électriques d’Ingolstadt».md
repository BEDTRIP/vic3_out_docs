---
type: concept
description: "Вид компании ««Frankenstein et Cie., Établ. Électriques d’Ingolstadt»» — ваниль 1.13, `company_ingolstadt_electrical_company`"
project: vic3
source: vanilla
aliases: ["«Frankenstein et Cie., Établ. Électriques d’Ingolstadt»", "Frankenstein et Cie., Établ. Électriques d’Ingolstadt", "company_ingolstadt_electrical_company"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ingolstadt_electrical_company
paths: [.vanillaVIC3/common/company_types/00_companies_totally_normal.txt]
---
# «Frankenstein et Cie., Établ. Électriques d’Ingolstadt»

Вид компании · `company_ingolstadt_electrical_company` · `common/company_types/00_companies_totally_normal.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ingolstadt_electrical_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAVARIA`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **possible_prestige_goods**: пусто
- **potential**: пусто
- **attainable**: скрипт, строки 25–30
- **possible**: скрипт, строки 32–49
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-frankenstein-company-bool|country_frankenstein_company_bool]] = `yes`
  - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 58–60
- **ai_construction_targets**: скрипт, строки 62–75
- **ai_weight**: скрипт, строки 77–79
