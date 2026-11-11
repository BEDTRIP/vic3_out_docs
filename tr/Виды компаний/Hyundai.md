---
type: concept
description: "Вид компании «Hyundai» — T&R 1.13, `company_hyundai`"
project: vic3
audience: agent
source: tr
aliases: ["Hyundai", "company_hyundai"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_hyundai
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Hyundai

Вид компании · `company_hyundai` · `common/company_types/ztr_automotive_companies.txt:355`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/south_korean_hyundai.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SEOUL`
- **building_types**: [[tr/Здания/Моторные заводы|Моторные заводы]], [[tr/Здания/Железные дороги|Железные дороги]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[tr/Здания/Верфи|Верфи]]
- **possible_prestige_goods**: `prestige_good_asia_automobiles`
- **prestige_goods_trigger**: скрипт, строки 373–378
- **potential**: скрипт, строки 379–381
- **attainable**: скрипт, строки 382–388
- **possible**: скрипт, строки 389–399
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.1` → [[tr/Здания/Верфи|Верфи]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.1`
- **ai_will_do**: скрипт, строки 404–410
- **ai_construction_targets**: скрипт, строки 411–418
- **ai_weight**: скрипт, строки 419–421
