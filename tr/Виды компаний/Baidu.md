---
type: concept
description: "Вид компании «Baidu» — T&R 1.13, `company_baidu`"
project: vic3
source: tr
aliases: ["Baidu", "company_baidu"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_baidu
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Baidu

Вид компании · `company_baidu` · `common/company_types/ztr_tech_companies.txt:943`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_baidu.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BEIJING`
- **building_types**: [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]], [[tr/Здания/Datacenters|Datacenters]]
- **potential**: скрипт, строки 955–957
- **attainable**: скрипт, строки 958–964
- **possible**: скрипт, строки 965–978
- **prosperity_modifier**:
  - `building_datacenter_industry_throughput_add` = `0.1` → [[tr/Здания/Datacenters|Datacenters]]
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.05`
- **ai_will_do**: скрипт, строки 983–989
- **ai_construction_targets**: скрипт, строки 990–997
- **ai_weight**: скрипт, строки 998–1000
