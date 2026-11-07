---
type: concept
description: "Вид компании ««Bolckow, Vaughan & Co.»» — VC 1.13, `company_bolckow_vaughan`"
project: vic3
source: vc
aliases: ["«Bolckow, Vaughan & Co.»", "Bolckow, Vaughan & Co", "company_bolckow_vaughan"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bolckow_vaughan
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Bolckow, Vaughan & Co.»]]"
---
# «Bolckow, Vaughan & Co.»

Вид компании · `company_bolckow_vaughan` · `common/company_types/joi_companies.txt:3857`

## Отличия от ваниль

- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_bolckow_vaughan_and_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_YORKSHIRE`
- **building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vc/Здания/Свинцовые рудники|Свинцовые рудники]]
- **possible_prestige_goods**: `prestige_good_sheffield_steel`
- **potential**: скрипт, строки 3879–3881
- **attainable**: скрипт, строки 3883–3889
- **possible**: скрипт, строки 3891–3905
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.2` → [[vc/Здания/верфи|верфи]]
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.2` → [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 3912–3918
- **ai_construction_targets**: скрипт, строки 3920–3939
- **ai_weight**: скрипт, строки 3941–3943
