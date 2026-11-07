---
type: concept
description: "Вид компании «Bertelsmann» — T&R 1.13, `company_bertelsmann`"
project: vic3
audience: agent
source: tr
aliases: ["Bertelsmann", "company_bertelsmann"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bertelsmann
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Bertelsmann

Вид компании · `company_bertelsmann` · `common/company_types/ztr_comunication_companies.txt:315`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/germany_bertelsmann.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WESTPHALIA`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **potential**: скрипт, строки 326–328
- **attainable**: скрипт, строки 329–335
- **possible**: скрипт, строки 336–346
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-society-tech-spread-mult|country_society_tech_spread_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-paper-mill-throughput-add|building_paper_mill_throughput_add]] = `0.05` → [[tr/Здания/Бумажные фабрики|Бумажные фабрики]]
- **ai_will_do**: скрипт, строки 352–358
- **ai_construction_targets**: скрипт, строки 359–366
- **ai_weight**: скрипт, строки 367–369
