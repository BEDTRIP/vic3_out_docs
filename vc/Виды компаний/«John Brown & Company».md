---
type: concept
description: "Вид компании ««John Brown & Company»» — VC 1.13, `company_john_brown`"
project: vic3
audience: agent
source: vc
aliases: ["«John Brown & Company»", "John Brown & Company", "company_john_brown"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_john_brown
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«John Brown & Company»]]"
---
# «John Brown & Company»

Вид компании · `company_john_brown` · `common/company_types/joi_companies.txt:4046`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_jb_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOWLANDS`, `STATE_ULSTER`
- **building_types**: [[vc/Здания/верфи|верфи]], [[vc/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Порты|Порты]]
- **possible_prestige_goods**: `prestige_good_clyde_built_liners`
- **potential**: скрипт, строки 4069–4071
- **attainable**: скрипт, строки 4073–4079
- **possible**: скрипт, строки 4081–4091
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-steamers-mult|goods_output_steamers_mult]] = `0.15` → [[vanilla/Товары/Пароходы|Пароходы]]
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-capital-ships-construction-efficiency-add|country_ship_group_capital_ships_construction_efficiency_add]] = `0.1`
- **ai_will_do**: скрипт, строки 4099–4105
- **ai_construction_targets**: скрипт, строки 4107–4114
- **ai_weight**: скрипт, строки 4116–4118
