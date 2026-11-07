---
type: concept
description: "Вид компании «Első Budapesti Gőzmalom Rt» — VC 1.13, `company_elso_budapesti_gozmalom`"
project: vic3
source: vc
aliases: ["Első Budapesti Gőzmalom Rt", "company_elso_budapesti_gozmalom"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_elso_budapesti_gozmalom
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Első Budapesti Gőzmalom Rt]]"
---
# Első Budapesti Gőzmalom Rt

Вид компании · `company_elso_budapesti_gozmalom` · `common/company_types/joi_companies.txt:8036`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_elso_budapesti_gozmalom.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Пшеничные поля|Пшеничные поля]], [[vc/Здания/Пищевые производства|Пищевые производства]], [[vc/Здания/Лесозаготовки|Лесозаготовки]]
- **extension_building_types**: [[vc/Здания/Виноградники|Виноградники]], [[vc/Здания/Плантации сахарного тростника|Плантации сахарного тростника]]
- **possible_prestige_goods**: `prestige_good_pannonian_patent_flour`
- **potential**: скрипт, строки 8057–8060
- **attainable**: пусто
- **possible**: скрипт, строки 8066–8088
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-mult|goods_output_grain_mult]] = `0.15` → [[vanilla/Товары/Зерно|Зерно]]
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 8096–8102
- **ai_construction_targets**: скрипт, строки 8104–8117
- **ai_weight**: скрипт, строки 8119–8121
