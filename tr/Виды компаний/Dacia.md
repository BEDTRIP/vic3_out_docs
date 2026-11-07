---
type: concept
description: "Вид компании «Dacia» — T&R 1.13, `company_dacia`"
project: vic3
audience: agent
source: tr
aliases: ["Dacia", "company_dacia"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_dacia
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_automotive_companies.txt]
---
# Dacia

Вид компании · `company_dacia` · `common/company_types/ztr_automotive_companies.txt:929`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/romanian_dacia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_automotive.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MOLDAVIA`
- **building_types**: [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_turin_automobiles`
- **potential**: скрипт, строки 942–944
- **attainable**: скрипт, строки 945–951
- **possible**: скрипт, строки 952–962
- **prosperity_modifier**:
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.05` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.1`
- **ai_will_do**: скрипт, строки 968–974
- **ai_construction_targets**: скрипт, строки 975–982
- **ai_weight**: скрипт, строки 983–985
