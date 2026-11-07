---
type: concept
description: "Вид компании «company_Kraus_Maffei» — grey USU 1.13, `company_Kraus_Maffei`"
project: vic3
source: grey_usu
aliases: ["company_Kraus_Maffei"]
tags: [grey_usu, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Kraus_Maffei
paths: [grey_add_alot_of_things/grey_usu/common/company_types/zMoG_USU_MUC_rail_company_updates.txt]
---
# company_Kraus_Maffei

Вид компании · `company_Kraus_Maffei` · `common/company_types/zMoG_USU_MUC_rail_company_updates.txt:1132`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/krauss.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BAVARIA`
- **possible_prestige_goods**: `prestige_good_generic_machine_parts`
- **building_types**: [[grey_usu/Здания/Железная дорога|Железная дорога]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[grey_usu/Здания/Железнодорожный терминал|Железнодорожный терминал]]
- **potential**: скрипт, строки 1153–1155
- **attainable**: скрипт, строки 1157–1163
- **possible**: скрипт, строки 1165–1174
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.04` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - `building_group_bg_usu_rail_infrastructure_throughput_add` = `0.09`
- **ai_will_do**: скрипт, строки 1182–1187
- **ai_construction_targets**: скрипт, строки 1189–1196
- **ai_weight**: скрипт, строки 1197–1199
