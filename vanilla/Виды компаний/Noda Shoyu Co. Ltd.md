---
type: concept
description: "Вид компании «Noda Shoyu Co. Ltd» — ваниль 1.13, `company_noda_shoyu`"
project: vic3
audience: agent
source: vanilla
aliases: ["Noda Shoyu Co. Ltd", "company_noda_shoyu"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_noda_shoyu
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Noda Shoyu Co. Ltd

Вид компании · `company_noda_shoyu` · `common/company_types/00_companies_ep2.txt:1280`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_noda_shoyu.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rice.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Рисовые поля|Рисовые поля]], [[vanilla/Здания/Виноградники|Виноградники]]
- **possible_prestige_goods**: `prestige_good_kikkoman_soy_sauce`
- **potential**: скрипт, строки 1301–1304
- **attainable**: скрипт, строки 1306–1314
- **possible**: скрипт, строки 1316–1326
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 1333–1337
- **ai_construction_targets**: скрипт, строки 1339–1346
- **ai_weight**: скрипт, строки 1348–1350
