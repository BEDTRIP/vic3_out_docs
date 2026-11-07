---
type: concept
description: "Вид компании ««Confédération générale des vignerons»» — VC 1.13, `company_cgv`"
project: vic3
source: vc
aliases: ["«Confédération générale des vignerons»", "Confédération générale des vignerons", "company_cgv"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_cgv
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Confédération générale des vignerons»]]"
---
# «Confédération générale des vignerons»

Вид компании · `company_cgv` · `common/company_types/joi_companies.txt:786`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_cgv.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rice.dds`
- **category**: `shopkeeper_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CHAMPAGNE`
- **building_types**: [[vc/Здания/Виноградники|Виноградники]], [[vanilla/Здания/Торговые центры|Торговые центры]]
- **extension_building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vc/Здания/Стеклозаводы|Стеклозаводы]], [[vanilla/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_champagne`
- **potential**: скрипт, строки 811–816
- **possible**: скрипт, строки 818–828
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-employee-mult|building_group_bg_agriculture_employee_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-wine-mult|goods_output_wine_mult]] = `0.25` → [[vanilla/Товары/Вино|Вино]]
- **ai_will_do**: скрипт, строки 836–842
- **ai_construction_targets**: скрипт, строки 844–851
- **ai_weight**: скрипт, строки 853–855
