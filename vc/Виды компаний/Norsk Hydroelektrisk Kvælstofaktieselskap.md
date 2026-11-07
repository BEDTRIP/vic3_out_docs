---
type: concept
description: "Вид компании «Norsk Hydroelektrisk Kvælstofaktieselskap» — VC 1.13, `company_norsk_hydro`"
project: vic3
audience: agent
source: vc
aliases: ["Norsk Hydroelektrisk Kvælstofaktieselskap", "company_norsk_hydro"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_norsk_hydro
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Norsk Hydroelektrisk Kvælstofaktieselskap]]"
---
# Norsk Hydroelektrisk Kvælstofaktieselskap

Вид компании · `company_norsk_hydro` · `common/company_types/joi_companies.txt:8759`

## Отличия от ваниль

- **potential**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_norsk_hydro.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WESTERN_NORWAY`
- **building_types**: [[vc/Здания/Заводы удобрений|Заводы удобрений]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vc/Здания/Серные рудники|Серные рудники]]
- **potential**: скрипт, строки 8776–8785
- **attainable**: скрипт, строки 8787–8795
- **possible**: скрипт, строки 8797–8810
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.15`
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-spread-mult|country_production_tech_spread_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 8818–8824
- **ai_construction_targets**: скрипт, строки 8826–8839
- **ai_weight**: скрипт, строки 8841–8843
