---
type: concept
description: "Вид компании ««Manufacture d'armes de Saint-Étienne»» — VC 1.13, `company_saint_etienne`"
project: vic3
source: vc
aliases: ["«Manufacture d'armes de Saint-Étienne»", "Manufacture d'armes de Saint-Étienne", "company_saint_etienne"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_saint_etienne
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Manufacture d'armes de Saint-Étienne»]]"
---
# «Manufacture d'armes de Saint-Étienne»

Вид компании · `company_saint_etienne` · `common/company_types/joi_companies.txt:3564`

## Отличия от ваниль

- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_saint_etienne.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RHONE`
- **building_types**: [[vc/Здания/Оружейные заводы|Оружейные заводы]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vc/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **possible_prestige_goods**: `prestige_good_saint_etienne_rifles`
- **potential**: скрипт, строки 3586–3588
- **attainable**: скрипт, строки 3590–3596
- **possible**: скрипт, строки 3598–3608
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-battle-defense-owned-province-mult|battle_defense_owned_province_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 3616–3622
- **ai_construction_targets**: скрипт, строки 3624–3631
- **ai_weight**: скрипт, строки 3633–3635
