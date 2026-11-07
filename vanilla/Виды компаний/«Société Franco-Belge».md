---
type: concept
description: "Вид компании ««Société Franco-Belge»» — ваниль 1.13, `company_franco_belge`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Société Franco-Belge»", "Société Franco-Belge", "company_franco_belge"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_franco_belge
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Société Franco-Belge»

Вид компании · `company_franco_belge` · `common/company_types/00_companies_europe.txt:79`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/franco_belge.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FLANDERS`, `STATE_WALLONIA`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **potential**: скрипт, строки 96–98
- **attainable**: скрипт, строки 100–109
- **possible**: скрипт, строки 111–123
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-mult|state_infrastructure_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 129–137
- **ai_construction_targets**: скрипт, строки 139–150
- **ai_weight**: скрипт, строки 152–154
