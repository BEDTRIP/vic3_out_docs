---
type: concept
description: "Вид компании «Norsk Hydroelektrisk Kvælstofaktieselskap» — ваниль 1.15, `company_norsk_hydro`"
project: vic3
audience: agent
source: vanilla
aliases: ["Norsk Hydroelektrisk Kvælstofaktieselskap", "company_norsk_hydro"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_norsk_hydro
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Norsk Hydroelektrisk Kvælstofaktieselskap

Вид компании · `company_norsk_hydro` · `common/company_types/00_companies_mp1.txt:1147`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_norsk_hydro.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WESTERN_NORWAY`
- **building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Медные рудники|Медные рудники]]
- **potential**: скрипт, строки 1165–1167
- **attainable**: скрипт, строки 1169–1177
- **possible**: скрипт, строки 1179–1192
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-spread-mult|country_production_tech_spread_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 1199–1205
- **ai_construction_targets**: скрипт, строки 1207–1220
- **ai_weight**: скрипт, строки 1222–1224
