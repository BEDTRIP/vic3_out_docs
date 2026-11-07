---
type: concept
description: "Вид компании «Volkswagen» — T&R 1.13, `company_volkswagen`"
project: vic3
source: tr
aliases: ["Volkswagen", "company_volkswagen"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_volkswagen
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Volkswagen

Вид компании · `company_volkswagen` · `common/company_types/ztr_automotive_companies.txt:490`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/german_volkswagen.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRUNSWICK`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Battery Plants|Battery Plants]], [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 508–510
- **attainable**: скрипт, строки 511–517
- **possible**: скрипт, строки 518–528
- **prosperity_modifier**:
  - `building_automotive_industry_throughput_add` = `0.1` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
  - `unit_combat_unit_type_modern_light_tanks_offense_mult` = `0.15`
  - `unit_combat_unit_type_modern_heavy_tank_offense_mult` = `0.15`
- **ai_will_do**: скрипт, строки 534–540
- **ai_construction_targets**: скрипт, строки 541–548
- **ai_weight**: скрипт, строки 549–551
