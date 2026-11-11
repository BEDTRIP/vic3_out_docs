---
type: concept
description: "Вид компании «Nissui» — VC 1.15, `company_nissui`"
project: vic3
audience: agent
source: vc
aliases: ["Nissui", "company_nissui"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nissui
paths: [VC/common/company_types/joi_companies.txt]
---
# Nissui

Вид компании · `company_nissui` · `common/company_types/joi_companies.txt:6078`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/company_nissui.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KYUSHU`
- **possible_prestige_goods**: `prestige_good_bluefin_tuna`
- **building_types**: [[vc/Здания/Рыболовные верфи|Рыболовные верфи]], [[vc/Здания/Китобойные станции|Китобойные станции]], [[vanilla/Здания/Торговые центры|Торговые центры]]
- **extension_building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Порты|Порты]]
- **potential**: скрипт, строки 6101–6104
- **attainable**: скрипт, строки 6106–6112
- **possible**: скрипт, строки 6114–6127
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-fish-mult|goods_output_fish_mult]] = `0.15` → [[vanilla/Товары/Рыба|Рыба]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-fishing-employee-mult|building_group_bg_fishing_employee_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-whaling-employee-mult|building_group_bg_whaling_employee_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 6135–6140
- **ai_construction_targets**: скрипт, строки 6142–6149
- **ai_weight**: скрипт, строки 6150–6152
