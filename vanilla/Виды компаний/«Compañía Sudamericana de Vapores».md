---
type: explanation
description: "Вид компании ««Compañía Sudamericana de Vapores»» — ваниль 1.15.2, `company_sudamericana_de_vapores`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Compañía Sudamericana de Vapores»", "Compañía Sudamericana de Vapores", "company_sudamericana_de_vapores"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sudamericana_de_vapores
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Compañía Sudamericana de Vapores»

Вид компании · `company_sudamericana_de_vapores` · `common/company_types/00_companies_cots.txt:546`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chile_csav.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SANTIAGO`
- **building_types**: [[vanilla/Здания/Верфи|Верфи]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **potential**: скрипт, строки 563–566
- **attainable**: скрипт, строки 568–574
- **possible**: скрипт, строки 576–588
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-colony-growth-speed-mult|state_colony_growth_speed_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-ship-group-supply-ships-construction-efficiency-add|country_ship_group_supply_ships_construction_efficiency_add]] = `0.1`
- **ai_will_do**: скрипт, строки 595–601
- **ai_construction_targets**: скрипт, строки 603–610
- **ai_weight**: скрипт, строки 612–614
