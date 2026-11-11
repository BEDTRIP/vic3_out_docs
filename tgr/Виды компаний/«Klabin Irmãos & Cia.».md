---
type: concept
description: "Вид компании ««Klabin Irmãos & Cia.»» — TGR 1.15, `company_kablin`"
project: vic3
audience: agent
source: tgr
aliases: ["«Klabin Irmãos & Cia.»", "Klabin Irmãos & Cia", "company_kablin"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_kablin
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Klabin Irmãos & Cia.»]]"
---
# «Klabin Irmãos & Cia.»

Вид компании · `company_kablin` · `common/company_types/TGR_TRADE_companies.txt:1004`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **possible**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_kablin_irmaos_and_cia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Кофейные плантации|Кофейные плантации]], [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]], [[vanilla/Здания/Каучуковые плантации|Каучуковые плантации]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_rosewood`, `prestige_good_generic_coffee`
- **potential**: скрипт, строки 1027–1029
- **attainable**: скрипт, строки 1031–1037
- **possible**: скрипт, строки 1039–1048
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-tooling-workshop-throughput-add|building_tooling_workshop_throughput_add]] = `0.1` → [[tgr/Здания/Производства инструментов|Производства инструментов]]
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `15`
- **ai_will_do**: скрипт, строки 1055–1060
- **ai_construction_targets**: скрипт, строки 1062–1070
- **ai_weight**: скрипт, строки 1072–1074
