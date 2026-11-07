---
type: concept
description: "Вид компании ««Schneider et Cie»» — T&R 1.13, `company_schneider_creusot`"
project: vic3
audience: agent
source: tr
aliases: ["«Schneider et Cie»", "Schneider et Cie", "company_schneider_creusot"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_schneider_creusot
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_france.txt]
replaces: "[[vanilla/Виды компаний/«Schneider et Cie»]]"
---
# «Schneider et Cie»

Вид компании · `company_schneider_creusot` · `common/company_types/ztr_companies_france.txt:2` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_schneider_et_cie.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BURGUNDY`
- **building_types**: [[tr/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[tr/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **extension_building_types**: [[tr/Здания/Железные дороги|Железные дороги]], [[tr/Здания/Robotics Industries|Robotics Industries]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **possible_prestige_goods**: `prestige_good_schneider_guns`
- **potential**: скрипт, строки 26–28
- **attainable**: скрипт, строки 30–36
- **possible**: скрипт, строки 38–48
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-loss-mult|unit_morale_loss_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 55–61
- **ai_construction_targets**: скрипт, строки 63–70
- **ai_weight**: скрипт, строки 72–74
