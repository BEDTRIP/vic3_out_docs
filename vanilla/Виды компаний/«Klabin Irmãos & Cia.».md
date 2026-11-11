---
type: concept
description: "Вид компании ««Klabin Irmãos & Cia.»» — ваниль 1.15, `company_kablin`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Klabin Irmãos & Cia.»", "Klabin Irmãos & Cia", "company_kablin"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_kablin
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «Klabin Irmãos & Cia.»

Вид компании · `company_kablin` · `common/company_types/00_companies_americas.txt:609`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_kablin_irmaos_and_cia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **extension_building_types**: [[vanilla/Здания/Серные рудники|Серные рудники]]
- **possible_prestige_goods**: `prestige_good_rosewood`
- **potential**: скрипт, строки 628–630
- **attainable**: скрипт, строки 632–638
- **possible**: скрипт, строки 640–650
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-tooling-workshop-throughput-add|building_tooling_workshop_throughput_add]] = `0.1` → [[vanilla/Здания/Производства инструментов|Производства инструментов]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `15`
- **ai_will_do**: скрипт, строки 657–663
- **ai_construction_targets**: скрипт, строки 665–673
- **ai_weight**: скрипт, строки 675–677
