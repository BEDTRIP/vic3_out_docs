---
type: concept
description: "Вид компании «Uraga Dock Company» — VC 1.15, `company_uragadockcompany`"
project: vic3
audience: agent
source: vc
aliases: ["Uraga Dock Company", "company_uragadockcompany"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_uragadockcompany
paths: [VC/common/company_types/joi_companies.txt]
---
# Uraga Dock Company

Вид компании · `company_uragadockcompany` · `common/company_types/joi_companies.txt:5991`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/uraga_dockcompany.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vc/Здания/Верфи|Верфи]], [[vanilla/Здания/Порты|Порты]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_artillery`
- **prestige_goods_trigger**: скрипт, строки 6016–6021
- **potential**: скрипт, строки 6023–6025
- **attainable**: скрипт, строки 6027–6033
- **possible**: скрипт, строки 6035–6049
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-critical-hit-multiplier-mult|ship_critical_hit_multiplier_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-navy-goods-cost-mult|country_navy_goods_cost_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-accuracy-mult|ship_accuracy_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 6058–6063
- **ai_construction_targets**: скрипт, строки 6065–6072
- **ai_weight**: скрипт, строки 6073–6075
