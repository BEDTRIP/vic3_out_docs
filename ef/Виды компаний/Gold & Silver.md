---
type: concept
description: "Вид компании «Gold & Silver» — E&F 1.13, `company_basic_gold_and_silver_mining_2`"
project: vic3
source: ef
aliases: ["Gold & Silver", "company_basic_gold_and_silver_mining_2"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_basic_gold_and_silver_mining_2
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Gold & Silver

Вид компании · `company_basic_gold_and_silver_mining_2` · `common/company_types/00_ef_companies.txt:6687`

## Поля

- **icon**: `gfx/interface/icons/company_icons/basic_gold_mining_2.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **replaces_company**: `company_basic_gold_and_silver_mining_2`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_consortium`, `dynamic_company_type_corporation`, `dynamic_company_type_conglomerate`, `dynamic_company_type_syndicate`, `dynamic_company_type_combine`
- **building_types**: [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]], [[ef/Здания/Торговые центры|Торговые центры]]
- **possible**: скрипт, строки 6711–6721
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-gold-mine-throughput-add|building_gold_mine_throughput_add]] = `0.25` → [[ef/Здания/Золотые рудники|Золотые рудники]]
  - [[vanilla/движок/Модификаторы B#^m-building-silver-mine-throughput-add|building_silver_mine_throughput_add]] = `0.25` → [[ef/Здания/Silver Mine|Silver Mine]]
