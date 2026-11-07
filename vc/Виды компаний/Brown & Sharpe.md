---
type: concept
description: "Вид компании «Brown & Sharpe» — VC 1.13, `company_brown_sharpe`"
project: vic3
audience: agent
source: vc
aliases: ["Brown & Sharpe", "company_brown_sharpe"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_brown_sharpe
paths: [VC/common/company_types/joi_companies.txt]
---
# Brown & Sharpe

Вид компании · `company_brown_sharpe` · `common/company_types/joi_companies.txt:7368`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/brown_sharpe.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RHODE_ISLAND`
- **building_types**: [[vc/Здания/Производства инструментов|Производства инструментов]], [[vc/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Свинцовые рудники|Свинцовые рудники]]
- **possible_prestige_goods**: `prestige_good_generic_tools`
- **potential**: скрипт, строки 7390–7392
- **attainable**: скрипт, строки 7394–7400
- **possible**: скрипт, строки 7402–7412
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-tools-mult|goods_output_tools_mult]] = `0.1` → [[vanilla/Товары/Инструменты|Инструменты]]
  - [[vanilla/движок/Модификаторы B#^m-building-arms-industry-throughput-add|building_arms_industry_throughput_add]] = `0.15` → [[vc/Здания/Оружейные заводы|Оружейные заводы]]
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.15` → [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 7420–7425
- **ai_construction_targets**: скрипт, строки 7427–7434
- **ai_weight**: скрипт, строки 7436–7438
