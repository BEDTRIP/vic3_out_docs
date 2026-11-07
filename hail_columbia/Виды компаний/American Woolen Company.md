---
type: concept
description: "Вид компании «American Woolen Company» — Hail Columbia 1.13, `company_usfp_american_woolen`"
project: vic3
source: hail_columbia
aliases: ["American Woolen Company", "company_usfp_american_woolen"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_american_woolen
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# American Woolen Company

Вид компании · `company_usfp_american_woolen` · `common/company_types/usfp_companies.txt:464`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_american_woolen.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CONNECTICUT`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации шёлка|Плантации шёлка]], [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]], [[vanilla/Здания/Плантации красильных растений|Плантации красильных растений]], [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 487–492
- **potential**: скрипт, строки 495–501
- **possible**: скрипт, строки 503–513
- **prosperity_modifier**:
  - `building_textile_mill_throughput_add` = `0.15` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
  - `interest_group_ig_industrialists_pol_str_mult` = `0.10`
- **ai_will_do**: скрипт, строки 520–529
- **ai_construction_targets**: скрипт, строки 531–538
- **ai_weight**: скрипт, строки 540–542
