---
type: concept
description: "Вид компании ««Tersâne-i Âmire»» — VC 1.13, `company_imperial_arsenal`"
project: vic3
source: vc
aliases: ["«Tersâne-i Âmire»", "Tersâne-i Âmire", "company_imperial_arsenal"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_imperial_arsenal
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Tersâne-i Âmire»]]"
---
# «Tersâne-i Âmire»

Вид компании · `company_imperial_arsenal` · `common/company_types/joi_companies.txt:1056`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: добавлено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/imperial_arsenal.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **building_types**: [[vc/Здания/верфи|верфи]], [[vc/Здания/Заводы взрывчатки|Заводы взрывчатки]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vc/Здания/Оружейные заводы|Оружейные заводы]]
- **extension_building_types**: [[vc/Здания/Автомобильные заводы|Автомобильные заводы]], [[vc/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Железные дороги|Железные дороги]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **possible_prestige_goods**: `prestige_good_abus_guns`
- **potential**: скрипт, строки 1084–1086
- **attainable**: скрипт, строки 1088–1094
- **possible**: скрипт, строки 1096–1106
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-critical-hit-chance-mult|ship_critical_hit_chance_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-battle-defense-owned-province-mult|battle_defense_owned_province_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-battle-offense-owned-province-mult|battle_offense_owned_province_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 1114–1120
- **ai_construction_targets**: скрипт, строки 1122–1129
- **ai_weight**: скрипт, строки 1131–1133
