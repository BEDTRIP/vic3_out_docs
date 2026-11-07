---
type: concept
description: "Вид компании «Massey-Harris Limited» — VC 1.13, `company_massey_harris`"
project: vic3
source: vc
aliases: ["Massey-Harris Limited", "company_massey_harris"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_massey_harris
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Massey-Harris Limited]]"
---
# Massey-Harris Limited

Вид компании · `company_massey_harris` · `common/company_types/joi_companies.txt:3786`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_massey_harris.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ONTARIO`, `STATE_WEST_COUNTRY`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Бумажные фабрики|Бумажные фабрики]]
- **possible_prestige_goods**: `prestige_good_irontill_series`
- **potential**: скрипт, строки 3809–3811
- **attainable**: пусто
- **possible**: скрипт, строки 3816–3828
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.15`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-employee-mult|building_group_bg_agriculture_employee_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 3835–3841
- **ai_construction_targets**: скрипт, строки 3843–3850
- **ai_weight**: скрипт, строки 3852–3854
