---
type: concept
description: "Вид компании «Mercedes-Benz» — T&R 1.13, `company_mercedes_benz`"
project: vic3
audience: agent
source: tr
aliases: ["Mercedes-Benz", "company_mercedes_benz"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mercedes_benz
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Mercedes-Benz

Вид компании · `company_mercedes_benz` · `common/company_types/ztr_automotive_companies.txt:425`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_mercedes_benz.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WURTTEMBERG`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 442–444
- **attainable**: скрипт, строки 445–451
- **possible**: скрипт, строки 452–462
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.1`
  - `building_battery_plant_throughput_add` = `0.05` → [[tr/Здания/Battery Plants|Battery Plants]]
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.05` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 469–475
- **ai_construction_targets**: скрипт, строки 476–483
- **ai_weight**: скрипт, строки 484–486
