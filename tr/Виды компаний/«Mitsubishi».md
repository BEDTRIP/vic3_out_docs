---
type: concept
description: "Вид компании ««Mitsubishi»» — T&R 1.13, `company_mitsubishi`"
project: vic3
audience: agent
source: tr
aliases: ["«Mitsubishi»", "Mitsubishi", "company_mitsubishi"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mitsubishi
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_japan.txt]
replaces: "[[vanilla/Виды компаний/«Mitsubishi»]]"
---
# «Mitsubishi»

Вид компании · `company_mitsubishi` · `common/company_types/ztr_companies_japan.txt:2` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **potential**: изменено
- **possible**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_mitsubishi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Верфи|Верфи]], [[tr/Здания/Бумажные фабрики|Бумажные фабрики]], [[tr/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[tr/Здания/Угольные шахты|Угольные шахты]], [[tr/Здания/Электростанции|Электростанции]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]], [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **possible_prestige_goods**: `prestige_good_washi_paper`
- **potential**: скрипт, строки 28–30
- **possible**: скрипт, строки 32–46
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.1` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **ai_will_do**: скрипт, строки 53–63
- **ai_construction_targets**: скрипт, строки 65–72
- **ai_weight**: скрипт, строки 74–76
