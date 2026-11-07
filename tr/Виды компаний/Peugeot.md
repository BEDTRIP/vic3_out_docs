---
type: concept
description: "Вид компании «Peugeot» — T&R 1.13, `company_peugeot`"
project: vic3
source: tr
aliases: ["Peugeot", "company_peugeot"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_peugeot
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Peugeot

Вид компании · `company_peugeot` · `common/company_types/ztr_automotive_companies.txt:681`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_peugeot.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FRANCHE_COMTE`
- **building_types**: [[tr/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[tr/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 698–700
- **attainable**: скрипт, строки 701–707
- **possible**: скрипт, строки 708–718
- **prosperity_modifier**:
  - `state_infrastructure_from_automobiles_consumption_add` = `0.1`
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.05` → [[tr/Здания/Oil Refineries|Oil Refineries]]
- **ai_will_do**: скрипт, строки 723–729
- **ai_construction_targets**: скрипт, строки 730–737
- **ai_weight**: скрипт, строки 738–740
