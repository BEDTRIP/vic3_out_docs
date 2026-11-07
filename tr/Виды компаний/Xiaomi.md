---
type: concept
description: "Вид компании «Xiaomi» — T&R 1.13, `company_xiaomi`"
project: vic3
source: tr
aliases: ["Xiaomi", "company_xiaomi"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_xiaomi
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Xiaomi

Вид компании · `company_xiaomi` · `common/company_types/ztr_automotive_companies.txt:20`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_xiaomi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BEIJING`
- **building_types**: [[tr/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_smartphones`, `prestige_good_asia_automobiles`
- **potential**: скрипт, строки 37–39
- **attainable**: скрипт, строки 40–46
- **possible**: скрипт, строки 47–57
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.1` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
  - `building_renewable_energy_power_plant_throughput_add` = `0.1` → [[tr/Здания/Renewable Energy Power Plants|Renewable Energy Power Plants]]
  - `country_prestige_mult` = `0.05`
- **ai_will_do**: скрипт, строки 63–69
- **ai_construction_targets**: скрипт, строки 70–77
- **ai_weight**: скрипт, строки 78–80
