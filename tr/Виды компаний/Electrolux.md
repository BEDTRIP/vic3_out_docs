---
type: concept
description: "Вид компании «Electrolux» — T&R 1.13, `company_electrolux`"
project: vic3
source: tr
aliases: ["Electrolux", "company_electrolux"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_electrolux
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_furniture_companies.txt]
---
# Electrolux

Вид компании · `company_electrolux` · `common/company_types/ztr_furniture_companies.txt:78`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swedish_electrolux.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **potential**: скрипт, строки 89–91
- **attainable**: скрипт, строки 92–99
- **possible**: скрипт, строки 100–110
- **prosperity_modifier**:
  - `building_fishing_wharf_throughput_add` = `0.1` → [[tr/Здания/Рыболовные верфи|Рыболовные верфи]]
  - `building_whaling_station_throughput_add` = `0.1` → [[tr/Здания/Китобойные станции|Китобойные станции]]
  - `building_livestock_ranch_throughput_add` = `0.1` → [[tr/Здания/Животноводческие фермы|Животноводческие фермы]]
  - `goods_output_homeappliances_mult` = `0.05` → [[tr/Товары/Home Appliances|Home Appliances]]
- **ai_will_do**: скрипт, строки 117–123
- **ai_construction_targets**: скрипт, строки 124–131
- **ai_weight**: скрипт, строки 132–134
