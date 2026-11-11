---
type: concept
description: "Вид компании «Yasuda» — ваниль 1.15, `company_yasuda`"
project: vic3
audience: agent
source: vanilla
aliases: ["Yasuda", "company_yasuda"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_yasuda
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Yasuda

Вид компании · `company_yasuda` · `common/company_types/00_companies_ep2.txt:103`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_yasuda.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 127–132
- **potential**: скрипт, строки 134–137
- **attainable**: скрипт, строки 139–147
- **possible**: скрипт, строки 149–168
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-gold-reserve-limit-mult|country_gold_reserve_limit_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 176–181
- **ai_construction_targets**: скрипт, строки 183–202
- **ai_weight**: скрипт, строки 204–206
