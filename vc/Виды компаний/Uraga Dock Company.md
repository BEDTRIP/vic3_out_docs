---
type: concept
description: "Вид компании «Uraga Dock Company» — VC 1.13, `company_uragadockcompany`"
project: vic3
source: vc
aliases: ["Uraga Dock Company", "company_uragadockcompany"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_uragadockcompany
paths: [VC/common/company_types/joi_companies.txt]
---
# Uraga Dock Company

Вид компании · `company_uragadockcompany` · `common/company_types/joi_companies.txt:5989`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/uraga_dockcompany.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vc/Здания/верфи|верфи]], [[vanilla/Здания/Порты|Порты]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_artillery`
- **prestige_goods_trigger**: скрипт, строки 6014–6019
- **potential**: скрипт, строки 6021–6023
- **attainable**: скрипт, строки 6025–6031
- **possible**: скрипт, строки 6033–6047
- **prosperity_modifier**:
  - `ship_critical_hit_multiplier_mult` = `0.1`
  - `country_navy_goods_cost_mult` = `-0.1`
  - `ship_accuracy_mult` = `0.05`
- **ai_will_do**: скрипт, строки 6056–6061
- **ai_construction_targets**: скрипт, строки 6063–6070
- **ai_weight**: скрипт, строки 6071–6073
