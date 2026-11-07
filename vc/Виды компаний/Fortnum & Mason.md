---
type: concept
description: "Вид компании «Fortnum & Mason» — VC 1.13, `company_Fortnum_Mason`"
project: vic3
audience: agent
source: vc
aliases: ["Fortnum & Mason", "company_Fortnum_Mason"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Fortnum_Mason
paths: [VC/common/company_types/joi_companies.txt]
---
# Fortnum & Mason

Вид компании · `company_Fortnum_Mason` · `common/company_types/joi_companies.txt:4122`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/Fortnum_Mason.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`, `STATE_WALES`, `STATE_MUNSTER`, `STATE_LANCASHIRE`
- **building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vc/Здания/Чайные плантации|Чайные плантации]], [[vc/Здания/Пшеничные поля|Пшеничные поля]]
- **extension_building_types**: [[vc/Здания/Стеклозаводы|Стеклозаводы]], [[vc/Здания/Рыболовные верфи|Рыболовные верфи]]
- **possible_prestige_goods**: `prestige_good_english_afternoon_tea`
- **potential**: скрипт, строки 4145–4147
- **attainable**: скрипт, строки 4149–4155
- **possible**: скрипт, строки 4157–4170
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.1` → [[vanilla/Здания/Городские центры|Городские центры]]
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.15`
- **ai_will_do**: скрипт, строки 4178–4183
- **ai_construction_targets**: скрипт, строки 4185–4192
- **ai_weight**: скрипт, строки 4194–4196
