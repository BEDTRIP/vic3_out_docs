---
type: concept
description: "Вид компании ««Schneider et Cie»» — ваниль 1.15, `company_schneider_creusot`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Schneider et Cie»", "Schneider et Cie", "company_schneider_creusot"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_schneider_creusot
paths: [.vanillaVIC3/common/company_types/00_companies_france.txt]
---
# «Schneider et Cie»

Вид компании · `company_schneider_creusot` · `common/company_types/00_companies_france.txt:67`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_schneider_et_cie.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BURGUNDY`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Верфи|Верфи]]
- **possible_prestige_goods**: `prestige_good_schneider_guns`
- **potential**: скрипт, строки 90–92
- **attainable**: скрипт, строки 94–100
- **possible**: скрипт, строки 102–110
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-loss-mult|unit_morale_loss_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 117–123
- **ai_construction_targets**: скрипт, строки 125–132
- **ai_weight**: скрипт, строки 134–142
