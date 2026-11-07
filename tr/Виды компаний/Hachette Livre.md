---
type: concept
description: "Вид компании «Hachette Livre» — T&R 1.13, `company_hachette_livre`"
project: vic3
source: tr
aliases: ["Hachette Livre", "company_hachette_livre"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_hachette_livre
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Hachette Livre

Вид компании · `company_hachette_livre` · `common/company_types/ztr_comunication_companies.txt:258`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_hachette_livre.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]]
- **potential**: скрипт, строки 268–270
- **attainable**: скрипт, строки 271–277
- **possible**: скрипт, строки 278–288
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-society-tech-research-speed-mult|country_society_tech_research_speed_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-add|state_education_access_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-paper-mill-throughput-add|building_paper_mill_throughput_add]] = `0.05` → [[tr/Здания/Бумажные фабрики|Бумажные фабрики]]
- **ai_will_do**: скрипт, строки 294–300
- **ai_construction_targets**: скрипт, строки 301–308
- **ai_weight**: скрипт, строки 309–311
