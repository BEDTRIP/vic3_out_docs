---
type: concept
description: "Вид компании ««Fábrica de Armas de Trubia»» — VC 1.13, `company_trubia`"
project: vic3
source: vc
aliases: ["«Fábrica de Armas de Trubia»", "Fábrica de Armas de Trubia", "company_trubia"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_trubia
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Fábrica de Armas de Trubia»]]"
---
# «Fábrica de Armas de Trubia»

Вид компании · `company_trubia` · `common/company_types/joi_companies.txt:6640`

## Отличия от ваниль

- **potential**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/spain_fabrica_de_armas_de_trubia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ASTURIAS`
- **building_types**: [[vc/Здания/Оружейные заводы|Оружейные заводы]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]], [[vc/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **possible_prestige_goods**: `prestige_good_generic_artillery`
- **prestige_goods_trigger**: скрипт, строки 6662–6667
- **potential**: скрипт, строки 6669–6672
- **attainable**: скрипт, строки 6674–6680
- **possible**: скрипт, строки 6682–6692
- **prosperity_modifier**:
  - `unit_offense_mult` = `0.1`
  - `unit_defense_mult` = `0.05`
  - `country_military_goods_cost_mult` = `-0.1`
- **ai_will_do**: скрипт, строки 6700–6706
- **ai_construction_targets**: скрипт, строки 6708–6715
- **ai_weight**: скрипт, строки 6717–6719
