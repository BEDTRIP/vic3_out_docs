---
type: concept
description: "Вид компании «Fininvest» — T&R 1.13, `company_fininvest`"
project: vic3
source: tr
aliases: ["Fininvest", "company_fininvest"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_fininvest
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Fininvest

Вид компании · `company_fininvest` · `common/company_types/ztr_comunication_companies.txt:431`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/italy_fininvest.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_media.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOMBARDY`, `STATE_LAZIO`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **extension_building_types**: [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **potential**: скрипт, строки 446–448
- **attainable**: скрипт, строки 449–455
- **possible**: скрипт, строки 456–466
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.1` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.02`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.05`
  - `goods_output_elgar_music_mult` = `0.05` → [[tr/Товары/Entertainment|Entertainment]]
- **ai_will_do**: скрипт, строки 473–479
- **ai_construction_targets**: скрипт, строки 480–487
- **ai_weight**: скрипт, строки 488–490
