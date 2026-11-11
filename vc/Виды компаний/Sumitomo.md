---
type: concept
description: "Вид компании «Sumitomo» — VC 1.15, `company_sumitomo`"
project: vic3
audience: agent
source: vc
aliases: ["Sumitomo", "company_sumitomo"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_sumitomo
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Sumitomo]]"
---
# Sumitomo

Вид компании · `company_sumitomo` · `common/company_types/joi_companies.txt:7601`

## Отличия от ваниль

- **prosperity_modifier**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_sumitomo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANSAI`
- **building_types**: [[vanilla/Здания/Медные рудники|Медные рудники]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Заводы удобрений|Заводы удобрений]]
- **extension_building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **potential**: скрипт, строки 7625–7627
- **attainable**: скрипт, строки 7629–7637
- **possible**: скрипт, строки 7639–7654
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.1` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-steel-mult|goods_output_steel_mult]] = `0.1` → [[vanilla/Товары/Сталь|Сталь]]
- **ai_will_do**: скрипт, строки 7662–7667
- **ai_construction_targets**: скрипт, строки 7669–7688
- **ai_weight**: скрипт, строки 7690–7692
