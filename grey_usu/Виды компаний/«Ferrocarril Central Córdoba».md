---
type: concept
description: "Вид компании ««Ferrocarril Central Córdoba»» — grey USU 1.13, `company_cordoba_railway`"
project: vic3
source: grey_usu
aliases: ["«Ferrocarril Central Córdoba»", "Ferrocarril Central Córdoba", "company_cordoba_railway"]
tags: [grey_usu, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_cordoba_railway
paths: [grey_add_alot_of_things/grey_usu/common/company_types/yMoG_USU_companies_rail_overwrite.txt]
replaces: "[[vanilla/Виды компаний/«Ferrocarril Central Córdoba»]]"
---
# «Ferrocarril Central Córdoba»

Вид компании · `company_cordoba_railway` · `common/company_types/yMoG_USU_companies_rail_overwrite.txt:176`

## Отличия от ваниль

- **building_types**: изменено
- **possible**: изменено
- **ai_construction_targets**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/argentina_cordoba_cenral_railway.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LA_PAMPA`
- **building_types**: [[grey_usu/Здания/Железнодорожный терминал|Железнодорожный терминал]], [[grey_usu/Здания/Железная дорога|Железная дорога]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **potential**: скрипт, строки 194–197
- **attainable**: скрипт, строки 199–205
- **possible**: скрипт, строки 207–223
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-wheat-farm-throughput-add|building_wheat_farm_throughput_add]] = `0.1` → [[vanilla/Здания/Пшеничные поля|Пшеничные поля]]
  - [[vanilla/движок/Модификаторы B#^m-building-livestock-ranch-throughput-add|building_livestock_ranch_throughput_add]] = `0.05` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **ai_will_do**: скрипт, строки 230–236
- **ai_construction_targets**: скрипт, строки 238–246
- **ai_weight**: скрипт, строки 248–250
