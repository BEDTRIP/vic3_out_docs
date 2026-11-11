---
type: concept
description: "Вид компании ««Stabilimento Tecnico Triestino»» — VC 1.15, `company_stt`"
project: vic3
audience: agent
source: vc
aliases: ["«Stabilimento Tecnico Triestino»", "Stabilimento Tecnico Triestino", "company_stt"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_stt
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Stabilimento Tecnico Triestino»]]"
---
# «Stabilimento Tecnico Triestino»

Вид компании · `company_stt` · `common/company_types/joi_companies.txt:7957`

## Отличия от ваниль

- **building_types**: изменено
- **possible_prestige_goods**: добавлено
- **prestige_goods_trigger**: добавлено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/stt.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ISTRIA`
- **building_types**: [[vc/Здания/Верфи|Верфи]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 7980–7985
- **potential**: скрипт, строки 7987–7989
- **attainable**: скрипт, строки 7991–7997
- **possible**: скрипт, строки 7999–8009
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-armor-mult|ship_armor_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-crew-damage-mult|ship_crew_damage_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.1`
- **ai_will_do**: скрипт, строки 8017–8023
- **ai_construction_targets**: скрипт, строки 8025–8032
- **ai_weight**: скрипт, строки 8034–8036
