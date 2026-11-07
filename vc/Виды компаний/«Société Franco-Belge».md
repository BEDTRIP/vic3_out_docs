---
type: concept
description: "Вид компании ««Société Franco-Belge»» — VC 1.13, `company_franco_belge`"
project: vic3
source: vc
aliases: ["«Société Franco-Belge»", "Société Franco-Belge", "company_franco_belge"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_franco_belge
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Société Franco-Belge»]]"
---
# «Société Franco-Belge»

Вид компании · `company_franco_belge` · `common/company_types/joi_companies.txt:6420`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **possible_prestige_goods**: добавлено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/franco_belge.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FLANDERS`, `STATE_NORMANDY`, `STATE_FRENCH_LOW_COUNTRIES`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Железные дороги|Железные дороги]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_tools`
- **potential**: скрипт, строки 6442–6444
- **attainable**: скрипт, строки 6446–6456
- **possible**: скрипт, строки 6458–6471
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-mult|state_infrastructure_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.15` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.15` → [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 6479–6488
- **ai_construction_targets**: скрипт, строки 6490–6502
- **ai_weight**: скрипт, строки 6504–6506
