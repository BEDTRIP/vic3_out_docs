---
type: concept
description: "Вид компании «Yasuda» — VC 1.15, `company_yasuda`"
project: vic3
audience: agent
source: vc
aliases: ["Yasuda", "company_yasuda"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_yasuda
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Yasuda]]"
---
# Yasuda

Вид компании · `company_yasuda` · `common/company_types/joi_companies.txt:7772`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **prosperity_modifier**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_yasuda.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vc/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Порты|Порты]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Текстильные фабрики|Текстильные фабрики]]
- **possible_prestige_goods**: `prestige_good_generic_tools`
- **potential**: скрипт, строки 7796–7799
- **attainable**: скрипт, строки 7801–7809
- **possible**: скрипт, строки 7811–7830
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 7838–7843
- **ai_construction_targets**: скрипт, строки 7845–7864
- **ai_weight**: скрипт, строки 7866–7868
