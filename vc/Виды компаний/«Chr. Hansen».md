---
type: concept
description: "Вид компании ««Chr. Hansen»» — VC 1.13, `company_chr_hansens`"
project: vic3
source: vc
aliases: ["«Chr. Hansen»", "Chr. Hansen", "company_chr_hansens"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_chr_hansens
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Chr. Hansen»]]"
---
# «Chr. Hansen»

Вид компании · `company_chr_hansens` · `common/company_types/joi_companies.txt:3282`

## Отличия от ваниль

- **extension_building_types**: изменено
- **prosperity_modifier**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/denmark_chr_hansens_teknisk_kemiske_laboratorium.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rye.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZEALAND`
- **building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vc/Здания/Заводы удобрений|Заводы удобрений]]
- **extension_building_types**: [[vc/Здания/Заводы синтетики|Заводы синтетики]], [[vc/Здания/Рыболовные верфи|Рыболовные верфи]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **potential**: скрипт, строки 3304–3306
- **attainable**: скрипт, строки 3308–3314
- **possible**: скрипт, строки 3316–3328
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-livestock-ranch-throughput-add|building_livestock_ranch_throughput_add]] = `0.15` → [[vc/Здания/Животноводческие фермы|Животноводческие фермы]]
  - [[vanilla/движок/Модификаторы B#^m-building-fishing-wharf-throughput-add|building_fishing_wharf_throughput_add]] = `0.15` → [[vc/Здания/Рыболовные верфи|Рыболовные верфи]]
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 3336–3341
- **ai_construction_targets**: скрипт, строки 3343–3356
- **ai_weight**: скрипт, строки 3358–3360
