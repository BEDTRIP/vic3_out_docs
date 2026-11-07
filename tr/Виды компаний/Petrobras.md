---
type: concept
description: "Вид компании «Petrobras» — T&R 1.13, `company_petrobas`"
project: vic3
source: tr
aliases: ["Petrobras", "company_petrobas"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_petrobas
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# Petrobras

Вид компании · `company_petrobas` · `common/company_types/ztr_oil_gas_companies.txt:10`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazilian_company_petrobas.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RIO_DE_JANEIRO`
- **building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **potential**: скрипт, строки 25–27
- **attainable**: скрипт, строки 28–38
- **possible**: скрипт, строки 39–51
- **prosperity_modifier**:
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.05` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-logging-throughput-add|building_group_bg_logging_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 57–66
- **ai_construction_targets**: скрипт, строки 67–77
- **ai_weight**: скрипт, строки 78–80
