---
type: concept
description: "Вид компании ««Chr. Hansen»» — ваниль 1.13, `company_chr_hansens`"
project: vic3
source: vanilla
aliases: ["«Chr. Hansen»", "Chr. Hansen", "company_chr_hansens"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_chr_hansens
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Chr. Hansen»

Вид компании · `company_chr_hansens` · `common/company_types/00_companies_europe.txt:1614`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/denmark_chr_hansens_teknisk_kemiske_laboratorium.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rye.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZEALAND`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **extension_building_types**: [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **prestige_goods_trigger**: скрипт, строки 1635–1640
- **potential**: скрипт, строки 1642–1644
- **attainable**: скрипт, строки 1646–1652
- **possible**: скрипт, строки 1654–1666
- **prosperity_modifier**:
  - `building_livestock_ranch_throughput_add` = `0.1` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
  - `building_fishing_wharf_throughput_add` = `0.1` → [[vanilla/Здания/Рыболовные верфи|Рыболовные верфи]]
- **ai_will_do**: скрипт, строки 1673–1678
- **ai_construction_targets**: скрипт, строки 1680–1693
- **ai_weight**: скрипт, строки 1695–1697
