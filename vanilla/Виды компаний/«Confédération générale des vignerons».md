---
type: concept
description: "Вид компании ««Confédération générale des vignerons»» — ваниль 1.13, `company_cgv`"
project: vic3
source: vanilla
aliases: ["«Confédération générale des vignerons»", "Confédération générale des vignerons", "company_cgv"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_cgv
paths: [.vanillaVIC3/common/company_types/00_companies_france.txt]
---
# «Confédération générale des vignerons»

Вид компании · `company_cgv` · `common/company_types/00_companies_france.txt:223`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_cgv.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rice.dds`
- **category**: `shopkeeper_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CHAMPAGNE`
- **building_types**: [[vanilla/Здания/Виноградники|Виноградники]]
- **extension_building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **possible_prestige_goods**: `prestige_good_champagne`
- **potential**: скрипт, строки 245–250
- **possible**: скрипт, строки 252–262
- **prosperity_modifier**:
  - `country_prestige_mult` = `0.15`
  - `building_vineyard_throughput_add` = `0.1` → [[vanilla/Здания/Виноградники|Виноградники]]
- **ai_will_do**: скрипт, строки 269–275
- **ai_construction_targets**: скрипт, строки 277–284
- **ai_weight**: скрипт, строки 286–288
