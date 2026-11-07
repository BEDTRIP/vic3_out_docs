---
type: concept
description: "Вид компании «Sinopec» — T&R 1.13, `company_sinopec`"
project: vic3
source: tr
aliases: ["Sinopec", "company_sinopec"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sinopec
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_oil_gas_companies.txt]
---
# Sinopec

Вид компании · `company_sinopec` · `common/company_types/ztr_oil_gas_companies.txt:84`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_company_sinopec.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_oil_drills.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BEIJING`, `STATE_SUZHOU`
- **building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **potential**: скрипт, строки 100–102
- **attainable**: скрипт, строки 103–111
- **possible**: скрипт, строки 112–120
- **prosperity_modifier**:
  - `building_rare_earths_mine_throughput_add` = `0.05` → [[tr/Здания/Rare Earths Mines|Rare Earths Mines]]
  - `building_power_plant_throughput_add` = `0.1` → [[tr/Здания/Электростанции|Электростанции]]
  - `building_railway_throughput_add` = `0.05` → [[tr/Здания/Железные дороги|Железные дороги]]
- **ai_will_do**: скрипт, строки 126–131
- **ai_weight**: скрипт, строки 132–134
