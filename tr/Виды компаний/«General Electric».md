---
type: concept
description: "Вид компании ««General Electric»» — T&R 1.13, `company_general_electric`"
project: vic3
source: tr
aliases: ["«General Electric»", "General Electric", "company_general_electric"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_general_electric
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_usa.txt]
replaces: "[[vanilla/Виды компаний/«General Electric»]]"
---
# «General Electric»

Вид компании · `company_general_electric` · `common/company_types/ztr_companies_usa.txt:44` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_general_electric.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MASSACHUSETTS`, `STATE_NEW_YORK`
- **building_types**: [[tr/Здания/Электрозаводы|Электрозаводы]], [[tr/Здания/Электростанции|Электростанции]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **extension_building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Robotics Industries|Robotics Industries]], [[tr/Здания/Renewable Energy Power Plants|Renewable Energy Power Plants]]
- **possible_prestige_goods**: `prestige_good_radiola_radios`
- **potential**: скрипт, строки 70–72
- **attainable**: скрипт, строки 74–83
- **possible**: скрипт, строки 85–98
- **prosperity_modifier**:
  - `building_motor_industry_throughput_add` = `0.05` → [[tr/Здания/Моторные заводы|Моторные заводы]]
  - `country_weekly_innovation_mult` = `0.05`
- **ai_will_do**: скрипт, строки 105–114
- **ai_construction_targets**: скрипт, строки 116–127
- **ai_weight**: скрипт, строки 129–131
