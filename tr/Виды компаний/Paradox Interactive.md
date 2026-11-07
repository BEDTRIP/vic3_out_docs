---
type: concept
description: "Вид компании «Paradox Interactive» — T&R 1.13, `company_paradox_interactive`"
project: vic3
source: tr
aliases: ["Paradox Interactive", "company_paradox_interactive"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_paradox_interactive
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_digital_media_industry.txt]
---
# Paradox Interactive

Вид компании · `company_paradox_interactive` · `common/company_types/ztr_digital_media_industry.txt:270`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swedish_paradox_interactive.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **extension_building_types**: [[tr/Здания/Академии искусств|Академии искусств]], [[tr/Здания/Software Industry|Software Industry]]
- **potential**: скрипт, строки 287–289
- **attainable**: скрипт, строки 290–297
- **possible**: скрипт, строки 298–308
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-experience-gain-mult|unit_experience_gain_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-university-throughput-add|building_university_throughput_add]] = `0.05` → [[vanilla/Здания/Университеты|Университеты]]
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 314–320
- **ai_construction_targets**: скрипт, строки 321–328
- **ai_weight**: скрипт, строки 329–331
