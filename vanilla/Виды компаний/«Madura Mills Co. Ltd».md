---
type: concept
description: "Вид компании ««Madura Mills Co. Ltd»» — ваниль 1.15, `company_madura_mills`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Madura Mills Co. Ltd»", "Madura Mills Co. Ltd", "company_madura_mills"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_madura_mills
paths: [.vanillaVIC3/common/company_types/00_companies_ip2.txt]
---
# «Madura Mills Co. Ltd»

Вид компании · `company_madura_mills` · `common/company_types/00_companies_ip2.txt:354`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ip2_madura_mills.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MADRAS`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]], [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 375–380
- **potential**: скрипт, строки 382–385
- **attainable**: скрипт, строки 387–393
- **possible**: скрипт, строки 395–403
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-petty-bourgeoisie-pop-attraction-mult|interest_group_ig_petty_bourgeoisie_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
  - [[vanilla/движок/Модификаторы C#^m-country-state-religion-wages-mult|country_state_religion_wages_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 411–416
- **ai_construction_targets**: скрипт, строки 418–425
- **ai_weight**: скрипт, строки 427–429
