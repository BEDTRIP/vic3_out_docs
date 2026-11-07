---
type: concept
description: "Вид компании «Toei Company» — T&R 1.13, `company_toei`"
project: vic3
audience: agent
source: tr
aliases: ["Toei Company", "company_toei"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_toei
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Toei Company

Вид компании · `company_toei` · `common/company_types/ztr_comunication_companies.txt:74`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_toei.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_media.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **possible_prestige_goods**: `prestige_good_japanese_anime_manga`
- **potential**: скрипт, строки 88–90
- **attainable**: скрипт, строки 91–97
- **possible**: скрипт, строки 98–108
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.05` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
  - `building_consumer_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]]
  - `building_interactive_media_industry_throughput_add` = `0.05` → [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **ai_will_do**: скрипт, строки 114–120
- **ai_construction_targets**: скрипт, строки 121–128
- **ai_weight**: скрипт, строки 129–131
