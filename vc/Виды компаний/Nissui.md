---
type: concept
description: "Вид компании «Nissui» — VC 1.13, `company_nissui`"
project: vic3
source: vc
aliases: ["Nissui", "company_nissui"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nissui
paths: [VC/common/company_types/joi_companies.txt]
---
# Nissui

Вид компании · `company_nissui` · `common/company_types/joi_companies.txt:6076`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/company_nissui.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KYUSHU`
- **possible_prestige_goods**: `prestige_good_bluefin_tuna`
- **building_types**: [[vc/Здания/Рыболовные верфи|Рыболовные верфи]], [[vc/Здания/Китобойные станции|Китобойные станции]], [[vanilla/Здания/Торговые центры|Торговые центры]]
- **extension_building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Порты|Порты]]
- **potential**: скрипт, строки 6099–6102
- **attainable**: скрипт, строки 6104–6110
- **possible**: скрипт, строки 6112–6125
- **prosperity_modifier**:
  - `goods_output_fish_mult` = `0.15` → [[vanilla/Товары/Рыба|Рыба]]
  - `building_group_bg_fishing_employee_mult` = `-0.25`
  - `building_group_bg_whaling_employee_mult` = `-0.25`
- **ai_will_do**: скрипт, строки 6133–6138
- **ai_construction_targets**: скрипт, строки 6140–6147
- **ai_weight**: скрипт, строки 6148–6150
