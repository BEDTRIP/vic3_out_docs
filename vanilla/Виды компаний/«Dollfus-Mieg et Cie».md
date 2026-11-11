---
type: concept
description: "Вид компании ««Dollfus-Mieg et Cie»» — ваниль 1.15, `company_dmc`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Dollfus-Mieg et Cie»", "Dollfus-Mieg et Cie", "company_dmc"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_dmc
paths: [.vanillaVIC3/common/company_types/00_companies_france.txt]
---
# «Dollfus-Mieg et Cie»

Вид компании · `company_dmc` · `common/company_types/00_companies_france.txt:146`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_dmc.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BURGUNDY`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Угольные шахты|Угольные шахты]]
- **extension_building_types**: [[vanilla/Здания/Плантации красильных растений|Плантации красильных растений]], [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 168–173
- **potential**: скрипт, строки 175–177
- **attainable**: скрипт, строки 179–185
- **possible**: скрипт, строки 187–195
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 201–206
- **ai_construction_targets**: скрипт, строки 208–215
- **ai_weight**: скрипт, строки 217–225
