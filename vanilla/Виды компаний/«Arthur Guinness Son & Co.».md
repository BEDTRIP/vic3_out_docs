---
type: concept
description: "Вид компании ««Arthur Guinness Son & Co.»» — ваниль 1.13, `company_guinness`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Arthur Guinness Son & Co.»", "Arthur Guinness Son & Co. Ltd", "company_guinness"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_guinness
paths: [.vanillaVIC3/common/company_types/00_companies_soi.txt]
---
# «Arthur Guinness Son & Co.»

Вид компании · `company_guinness` · `common/company_types/00_companies_soi.txt:1025`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/arthur_guinness_son.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LEINSTER`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Ржаные поля|Ржаные поля]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **prestige_goods_trigger**: скрипт, строки 1046–1051
- **potential**: скрипт, строки 1053–1055
- **attainable**: скрипт, строки 1057–1063
- **possible**: скрипт, строки 1065–1075
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-violent-hostility-mult|state_radicalism_increases_violent_hostility_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-cultural-erasure-mult|state_radicalism_increases_cultural_erasure_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicalism-increases-open-prejudice-mult|state_radicalism_increases_open_prejudice_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 1084–1090
- **ai_construction_targets**: скрипт, строки 1092–1099
- **ai_weight**: скрипт, строки 1101–1103
