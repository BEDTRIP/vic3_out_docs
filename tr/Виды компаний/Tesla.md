---
type: concept
description: "Вид компании «Tesla» — T&R 1.13, `company_tesla`"
project: vic3
source: tr
aliases: ["Tesla", "company_tesla"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_tesla
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Tesla

Вид компании · `company_tesla` · `common/company_types/ztr_automotive_companies.txt:804`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_tesla.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_TEXAS`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Battery Plants|Battery Plants]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_ford_automobiles`
- **potential**: скрипт, строки 819–821
- **attainable**: скрипт, строки 822–828
- **possible**: скрипт, строки 829–839
- **prosperity_modifier**:
  - `building_processors_foundry_throughput_add` = `0.05` → [[tr/Здания/Chip Foundries|Chip Foundries]]
  - `building_renewable_energy_power_plant_throughput_add` = `0.05` → [[tr/Здания/Renewable Energy Power Plants|Renewable Energy Power Plants]]
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 845–851
- **ai_construction_targets**: скрипт, строки 852–859
- **ai_weight**: скрипт, строки 860–862
