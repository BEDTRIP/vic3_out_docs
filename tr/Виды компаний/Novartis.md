---
type: concept
description: "Вид компании «Novartis» — T&R 1.13, `company_novartis`"
project: vic3
audience: agent
source: tr
aliases: ["Novartis", "company_novartis"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_novartis
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_pharma_companies.txt]
---
# Novartis

Вид компании · `company_novartis` · `common/company_types/ztr_pharma_companies.txt:69`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swiss_novartis.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/curtiss_comp_illu_pharma.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WEST_SWITZERLAND`
- **building_types**: [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **potential**: скрипт, строки 79–81
- **attainable**: скрипт, строки 82–89
- **possible**: скрипт, строки 90–100
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.02`
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 105–111
- **ai_construction_targets**: скрипт, строки 112–119
- **ai_weight**: скрипт, строки 120–122
