---
type: concept
description: "Вид компании ««G. Ricordi & C.»» — VC 1.13, `company_ricordi`"
project: vic3
source: vc
aliases: ["«G. Ricordi & C.»", "G. Ricordi & C", "company_ricordi"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ricordi
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«G. Ricordi & C.»]]"
---
# «G. Ricordi & C.»

Вид компании · `company_ricordi` · `common/company_types/joi_companies.txt:7143`

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
- **potential**: скрипт, строки 7165–7171
- **attainable**: пусто
- **possible**: скрипт, строки 7177–7188
- **prosperity_modifier**:
  - `country_prestige_mult` = `0.15`
  - `building_group_bg_arts_employee_mult` = `-0.1`
  - `goods_output_fine_art_mult` = `0.1` → [[vanilla/Товары/Картины|Картины]]
- **ai_will_do**: скрипт, строки 7196–7201
- **ai_construction_targets**: скрипт, строки 7203–7210
- **ai_weight**: скрипт, строки 7212–7214
