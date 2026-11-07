---
type: concept
description: "Вид компании «Maple & Co» — VC 1.13, `company_maple_and_co`"
project: vic3
audience: agent
source: vc
aliases: ["Maple & Co", "company_maple_and_co"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_maple_and_co
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Maple & Co]]"
---
# Maple & Co

Вид компании · `company_maple_and_co` · `common/company_types/joi_companies.txt:1672`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **attainable**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_maple_and_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`, `STATE_MIDLANDS`, `STATE_EAST_ANGLIA`, `STATE_LEINSTER`
- **building_types**: [[vc/Здания/Мебельные фабрики|Мебельные фабрики]], [[vc/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[vc/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_english_upholstery`
- **potential**: скрипт, строки 1693–1696
- **attainable**: пусто
- **possible**: скрипт, строки 1701–1710
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-government-throughput-add|building_group_bg_government_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-luxury-furniture-mult|goods_output_luxury_furniture_mult]] = `0.1` → [[vanilla/Товары/Роскошная мебель|Роскошная мебель]]
- **ai_will_do**: скрипт, строки 1718–1723
- **ai_construction_targets**: скрипт, строки 1725–1732
- **ai_weight**: скрипт, строки 1734–1736
