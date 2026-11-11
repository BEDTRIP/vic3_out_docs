---
type: concept
description: "Вид компании ««Bolckow, Vaughan & Co.»» — ваниль 1.15, `company_bolckow_vaughan`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Bolckow, Vaughan & Co.»", "Bolckow, Vaughan & Co", "company_bolckow_vaughan"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bolckow_vaughan
paths: [.vanillaVIC3/common/company_types/00_companies_great_britain.txt]
---
# «Bolckow, Vaughan & Co.»

Вид компании · `company_bolckow_vaughan` · `common/company_types/00_companies_great_britain.txt:293`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_bolckow_vaughan_and_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_YORKSHIRE`
- **building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **possible_prestige_goods**: `prestige_good_sheffield_steel`
- **potential**: скрипт, строки 315–317
- **attainable**: скрипт, строки 319–325
- **possible**: скрипт, строки 327–341
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.1` → [[vanilla/Здания/Верфи|Верфи]]
- **ai_will_do**: скрипт, строки 347–353
- **ai_construction_targets**: скрипт, строки 355–374
- **ai_weight**: скрипт, строки 376–378
