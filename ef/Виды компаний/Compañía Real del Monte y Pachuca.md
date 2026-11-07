---
type: concept
description: "Вид компании «Compañía Real del Monte y Pachuca» — E&F 1.13, `company_basic_silver_mining_mex`"
project: vic3
source: ef
aliases: ["Compañía Real del Monte y Pachuca", "company_basic_silver_mining_mex"]
tags: [ef, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_basic_silver_mining_mex
paths: [E&F/common/company_types/00_ef_companies.txt]
---
# Compañía Real del Monte y Pachuca

Вид компании · `company_basic_silver_mining_mex` · `common/company_types/00_ef_companies.txt:6730`

## Поля

- **icon**: `gfx/interface/icons/company_icons/company_basic_silver_mining_mex.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RIO_GRANDE`
- **possible_prestige_goods**: `prestige_good_mexican_silver`
- **building_types**: [[ef/Здания/Золотые рудники|Золотые рудники]], [[ef/Здания/Silver Mine|Silver Mine]]
- **potential**: скрипт, строки 6747–6749
- **possible**: скрипт, строки 6751–6761
- **attainable**: скрипт, строки 6763–6769
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-silver-mine-throughput-add|building_silver_mine_throughput_add]] = `0.25` → [[ef/Здания/Silver Mine|Silver Mine]]
- **ai_will_do**: скрипт, строки 6775–6780
- **ai_weight**: скрипт, строки 6782–6784
