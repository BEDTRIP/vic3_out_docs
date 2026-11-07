---
type: concept
description: "Вид компании «Yasuda» — VC 1.13, `company_yasuda`"
project: vic3
source: vc
aliases: ["Yasuda", "company_yasuda"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_yasuda
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Yasuda]]"
---
# Yasuda

Вид компании · `company_yasuda` · `common/company_types/joi_companies.txt:7769`

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
- **potential**: скрипт, строки 7793–7796
- **attainable**: скрипт, строки 7798–7806
- **possible**: скрипт, строки 7808–7827
- **prosperity_modifier**:
  - `interest_group_ig_industrialists_pol_str_mult` = `0.25`
  - `country_loan_interest_rate_mult` = `-0.1`
  - `state_birth_rate_mult` = `0.1`
- **ai_will_do**: скрипт, строки 7835–7840
- **ai_construction_targets**: скрипт, строки 7842–7861
- **ai_weight**: скрипт, строки 7863–7865
