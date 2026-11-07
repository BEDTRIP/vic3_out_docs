---
type: concept
description: "Вид компании ««Bunge y Born»» — VC 1.13, `company_bunge_born`"
project: vic3
source: vc
aliases: ["«Bunge y Born»", "Bunge & Born", "company_bunge_born"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bunge_born
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Bunge y Born»]]"
---
# «Bunge y Born»

Вид компании · `company_bunge_born` · `common/company_types/joi_companies.txt:3116`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/argentina_bunge_y_born.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Пшеничные поля|Пшеничные поля]], [[vc/Здания/Маисовые поля|Маисовые поля]], [[vc/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vc/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **prestige_goods_trigger**: скрипт, строки 3136–3141
- **potential**: скрипт, строки 3143–3145
- **attainable**: скрипт, строки 3147–3153
- **possible**: скрипт, строки 3155–3168
- **prosperity_modifier**:
  - `interest_group_ig_rural_folk_pop_attraction_mult` = `0.25`
  - `building_tooling_workshop_throughput_add` = `0.1` → [[vc/Здания/Производства инструментов|Производства инструментов]]
  - `state_birth_rate_mult` = `0.1`
- **ai_will_do**: скрипт, строки 3176–3181
- **ai_construction_targets**: скрипт, строки 3183–3198
- **ai_weight**: скрипт, строки 3200–3202
