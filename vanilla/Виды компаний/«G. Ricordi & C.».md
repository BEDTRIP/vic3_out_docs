---
type: concept
description: "Вид компании ««G. Ricordi & C.»» — ваниль 1.13, `company_ricordi`"
project: vic3
audience: agent
source: vanilla
aliases: ["«G. Ricordi & C.»", "G. Ricordi & C", "company_ricordi"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ricordi
paths: [.vanillaVIC3/common/company_types/00_companies_italy.txt]
---
# «G. Ricordi & C.»

Вид компании · `company_ricordi` · `common/company_types/00_companies_italy.txt:177`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ricordi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_corn.dds`
- **category**: `academic_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOMBARDY`
- **building_types**: [[vanilla/Здания/Академии искусств|Академии искусств]]
- **extension_building_types**: [[vanilla/Здания/Виноградники|Виноградники]]
- **potential**: скрипт, строки 195–197
- **attainable**: скрипт, строки 199–205
- **possible**: скрипт, строки 207–216
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-loyalists-from-political-movements-mult|state_loyalists_from_political_movements_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 223–228
- **ai_construction_targets**: скрипт, строки 230–237
- **ai_weight**: скрипт, строки 239–241
