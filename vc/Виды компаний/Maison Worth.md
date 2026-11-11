---
type: concept
description: "Вид компании «Maison Worth» — VC 1.15, `company_maison_worth`"
project: vic3
audience: agent
source: vc
aliases: ["Maison Worth", "company_maison_worth"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_maison_worth
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Maison Worth]]"
---
# Maison Worth

Вид компании · `company_maison_worth` · `common/company_types/joi_companies.txt:3639`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_weight**: изменено
- **category**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_maison_worth.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[vc/Здания/Текстильные фабрики|Текстильные фабрики]], [[vc/Здания/Плантации хлопка|Плантации хлопка]], [[vanilla/Здания/Академии искусств|Академии искусств]]
- **extension_building_types**: [[vc/Здания/Плантации шёлка|Плантации шёлка]], [[vc/Здания/Заводы синтетики|Заводы синтетики]]
- **possible_prestige_goods**: `prestige_good_haute_couture`
- **potential**: скрипт, строки 3662–3665
- **attainable**: пусто
- **possible**: скрипт, строки 3670–3679
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-luxury-clothes-mult|goods_output_luxury_clothes_mult]] = `0.05` → [[vanilla/Товары/Роскошная одежда|Роскошная одежда]]
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.25`
- **ai_will_do**: скрипт, строки 3687–3692
- **ai_construction_targets**: скрипт, строки 3694–3701
- **ai_weight**: скрипт, строки 3703–3705
