---
type: concept
description: "Вид компании ««Compañía Estañífera de Llallagua»» — ваниль 1.13, `company_estanifera_llallagua`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Compañía Estañífera de Llallagua»", "Compañía Estañífera de Llallagua", "company_estanifera_llallagua"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_estanifera_llallagua
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Compañía Estañífera de Llallagua»

Вид компании · `company_estanifera_llallagua` · `common/company_types/00_companies_cots.txt:409`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/bolivia_compania_estanifera_de_llallagua.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_POTOSI`
- **building_types**: [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **extension_building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Серные рудники|Серные рудники]]
- **potential**: скрипт, строки 426–429
- **attainable**: скрипт, строки 431–437
- **possible**: скрипт, строки 439–448
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-lead-mine-throughput-add|building_lead_mine_throughput_add]] = `0.1` → [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.15`
- **ai_will_do**: скрипт, строки 455–460
- **ai_construction_targets**: скрипт, строки 462–469
- **ai_weight**: скрипт, строки 471–473
