---
type: concept
description: "Вид компании «Renault» — T&R 1.13, `company_renault`"
project: vic3
audience: agent
source: tr
aliases: ["Renault", "company_renault"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_renault
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Renault

Вид компании · `company_renault` · `common/company_types/ztr_automotive_companies.txt:744`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/french_renault.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 758–760
- **attainable**: скрипт, строки 761–767
- **possible**: скрипт, строки 768–778
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы M#^m-military-formation-army-movement-speed-mult|military_formation_army_movement_speed_mult]] = `0.05`
  - `building_battery_plant_throughput_add` = `0.1` → [[tr/Здания/Battery Plants|Battery Plants]]
- **ai_will_do**: скрипт, строки 783–789
- **ai_construction_targets**: скрипт, строки 790–797
- **ai_weight**: скрипт, строки 798–800
