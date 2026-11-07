---
type: concept
description: "Вид компании «Westinghouse Electric & Manufacturing Company» — Hail Columbia 1.13, `company_usfp_westinghouse`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Westinghouse Electric & Manufacturing Company", "company_usfp_westinghouse"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_westinghouse
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# Westinghouse Electric & Manufacturing Company

Вид компании · `company_usfp_westinghouse` · `common/company_types/usfp_companies.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_westinghouse.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PENNSYLVANIA`, `STATE_MASSACHUSETTS`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]], [[vanilla/Здания/Оружейные заводы|Оружейные заводы]]
- **potential**: скрипт, строки 20–22
- **attainable**: скрипт, строки 24–33
- **possible**: скрипт, строки 35–48
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.10` → [[vanilla/Здания/Электростанции|Электростанции]]
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `0.10`
- **ai_will_do**: скрипт, строки 55–64
- **ai_construction_targets**: скрипт, строки 66–77
- **ai_weight**: скрипт, строки 79–81
