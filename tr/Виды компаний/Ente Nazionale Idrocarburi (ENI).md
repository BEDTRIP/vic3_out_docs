---
type: concept
description: "Вид компании «Ente Nazionale Idrocarburi (ENI)» — T&R 1.13, `company_eni`"
project: vic3
source: tr
aliases: ["Ente Nazionale Idrocarburi (ENI)", "company_eni"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_eni
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# Ente Nazionale Idrocarburi (ENI)

Вид компании · `company_eni` · `common/company_types/ztr_oil_gas_companies.txt:244`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/italian_company_eni.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LAZIO`
- **building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **potential**: скрипт, строки 259–261
- **attainable**: скрипт, строки 262–270
- **possible**: скрипт, строки 271–279
- **prosperity_modifier**:
  - `building_mendelejew_synthetic_rubber_factory_throughput_add` = `0.1` → [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.1` → [[tr/Здания/Железные дороги|Железные дороги]]
  - `building_renewable_energy_power_plant_throughput_add` = `-0.05` → [[tr/Здания/Renewable Energy Power Plants|Renewable Energy Power Plants]]
- **ai_will_do**: скрипт, строки 285–290
- **ai_construction_targets**: скрипт, строки 291–301
- **ai_weight**: скрипт, строки 302–304
