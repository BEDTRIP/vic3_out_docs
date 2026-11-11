---
type: concept
description: "Вид компании ««G. Ricordi & C.»» — VC 1.15, `company_ricordi`"
project: vic3
audience: agent
source: vc
aliases: ["«G. Ricordi & C.»", "G. Ricordi & C", "company_ricordi"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ricordi
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«G. Ricordi & C.»]]"
---
# «G. Ricordi & C.»

Вид компании · `company_ricordi` · `common/company_types/joi_companies.txt:7146`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **possible_prestige_goods**: добавлено
- **potential**: изменено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ricordi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_corn.dds`
- **category**: `academic_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`, `STATE_LOMBARDY`
- **building_types**: [[vanilla/Здания/Академии искусств|Академии искусств]]
- **extension_building_types**: [[vc/Здания/Виноградники|Виноградники]]
- **possible_prestige_goods**: `prestige_good_ricordi_opera`
- **potential**: скрипт, строки 7168–7174
- **attainable**: пусто
- **possible**: скрипт, строки 7180–7191
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-arts-employee-mult|building_group_bg_arts_employee_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-mult|goods_output_fine_art_mult]] = `0.1` → [[vanilla/Товары/Картины|Картины]]
- **ai_will_do**: скрипт, строки 7199–7204
- **ai_construction_targets**: скрипт, строки 7206–7213
- **ai_weight**: скрипт, строки 7215–7217
