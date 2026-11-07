---
type: concept
description: "Вид компании «Oesterreichisch-Alpine Montangesellschaft» — VC 1.13, `company_oesterreichisch_alpine_montangesellschaft`"
project: vic3
source: vc
aliases: ["Oesterreichisch-Alpine Montangesellschaft", "company_oesterreichisch_alpine_montangesellschaft"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_oesterreichisch_alpine_montangesellschaft
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Oesterreichisch-Alpine Montangesellschaft]]"
---
# Oesterreichisch-Alpine Montangesellschaft

Вид компании · `company_oesterreichisch_alpine_montangesellschaft` · `common/company_types/joi_companies.txt:5928`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: добавлено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: убрано
- **ai_construction_targets**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_oesterreichisch_alpine_montangesellschaft.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Угольные шахты|Угольные шахты]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vc/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **potential**: скрипт, строки 5949–5951
- **attainable**: скрипт, строки 5953–5961
- **possible**: скрипт, строки 5963–5976
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-lead-mine-throughput-add|building_lead_mine_throughput_add]] = `0.1` → [[vc/Здания/Свинцовые рудники|Свинцовые рудники]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.1` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.15`
- **ai_weight**: скрипт, строки 5984–5986
