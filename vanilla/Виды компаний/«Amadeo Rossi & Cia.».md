---
type: concept
description: "Вид компании ««Amadeo Rossi & Cia.»» — ваниль 1.13, `company_rossi`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Amadeo Rossi & Cia.»", "Amadeo Rossi & Cia", "company_rossi"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rossi
paths: [.vanillaVIC3/common/company_types/00_companies_cots.txt]
---
# «Amadeo Rossi & Cia.»

Вид компании · `company_rossi` · `common/company_types/00_companies_cots.txt:330`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_amadeo_rossi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RIO_GRANDE_DO_SUL`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **possible_prestige_goods**: `prestige_good_generic_small_arms`
- **prestige_goods_trigger**: скрипт, строки 351–356
- **potential**: скрипт, строки 358–361
- **attainable**: скрипт, строки 363–369
- **possible**: скрипт, строки 371–380
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-livestock-ranch-throughput-add|building_livestock_ranch_throughput_add]] = `0.1` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
  - [[vanilla/движок/Модификаторы B#^m-building-chemical-plant-throughput-add|building_chemical_plant_throughput_add]] = `0.05` → [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **ai_will_do**: скрипт, строки 387–392
- **ai_construction_targets**: скрипт, строки 394–401
- **ai_weight**: скрипт, строки 403–405
