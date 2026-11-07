---
type: concept
description: "Вид компании «Amsterdam Admiralty Shipyard» — VC 1.13, `company_admiralty_rijkswerf`"
project: vic3
audience: agent
source: vc
aliases: ["Amsterdam Admiralty Shipyard", "company_admiralty_rijkswerf"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_admiralty_rijkswerf
paths: [VC/common/company_types/joi_companies.txt]
---
# Amsterdam Admiralty Shipyard

Вид компании · `company_admiralty_rijkswerf` · `common/company_types/joi_companies.txt:6884`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/admiralty_rijkswerf.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`
- **building_types**: [[vanilla/Здания/Порты|Порты]], [[vc/Здания/верфи|верфи]]
- **extension_building_types**: [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **potential**: скрипт, строки 6907–6913
- **attainable**: скрипт, строки 6915–6921
- **possible**: скрипт, строки 6923–6933
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-armor-mult|ship_armor_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-ship-detection-mult|ship_detection_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-ship-construction-efficiency-add|country_ship_construction_efficiency_add]] = `0.1`
- **ai_will_do**: скрипт, строки 6941–6946
- **ai_construction_targets**: скрипт, строки 6948–6955
- **ai_weight**: скрипт, строки 6958–6960
