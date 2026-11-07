---
type: concept
description: "Вид компании ««Mitsubishi»» — VC 1.13, `company_mitsubishi`"
project: vic3
audience: agent
source: vc
aliases: ["«Mitsubishi»", "Mitsubishi", "company_mitsubishi"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mitsubishi
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Mitsubishi»]]"
---
# «Mitsubishi»

Вид компании · `company_mitsubishi` · `common/company_types/joi_companies.txt:2619`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **potential**: изменено
- **prosperity_modifier**: изменено
- **ai_construction_targets**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_mitsubishi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vc/Здания/верфи|верфи]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Бумажные фабрики|Бумажные фабрики]], [[vc/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vc/Здания/Автомобильные заводы|Автомобильные заводы]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **possible_prestige_goods**: `prestige_good_washi_paper`
- **potential**: скрипт, строки 2646–2648
- **possible**: скрипт, строки 2650–2664
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-automobiles-mult|goods_output_automobiles_mult]] = `0.1` → [[vanilla/Товары/Автомобили|Автомобили]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-paper-mult|goods_output_paper_mult]] = `0.15` → [[vanilla/Товары/Бумага|Бумага]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-approval-add|interest_group_ig_industrialists_approval_add]] = `3`
- **ai_will_do**: скрипт, строки 2672–2682
- **ai_construction_targets**: скрипт, строки 2684–2697
- **ai_weight**: скрипт, строки 2699–2701
