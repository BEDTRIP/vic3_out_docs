---
type: concept
description: "Вид компании «Studio Ghibli» — T&R 1.13, `company_studio_ghibli`"
project: vic3
audience: agent
source: tr
aliases: ["Studio Ghibli", "company_studio_ghibli"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_studio_ghibli
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Studio Ghibli

Вид компании · `company_studio_ghibli` · `common/company_types/ztr_comunication_companies.txt:135`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_studio_ghibli.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_media.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]]
- **possible_prestige_goods**: `prestige_good_japanese_anime_manga`
- **potential**: скрипт, строки 148–150
- **attainable**: скрипт, строки 151–157
- **possible**: скрипт, строки 158–168
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-rural-folk-approval-add|interest_group_ig_rural_folk_approval_add]] = `1`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-approval-add|interest_group_ig_intelligentsia_approval_add]] = `1`
- **ai_will_do**: скрипт, строки 175–181
- **ai_construction_targets**: скрипт, строки 182–189
- **ai_weight**: скрипт, строки 190–192
