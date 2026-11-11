---
type: concept
description: "Вид компании ««Schneider et Cie»» — VC 1.15, `company_schneider_creusot`"
project: vic3
audience: agent
source: vc
aliases: ["«Schneider et Cie»", "Schneider et Cie", "company_schneider_creusot"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_schneider_creusot
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Schneider et Cie»]]"
---
# «Schneider et Cie»

Вид компании · `company_schneider_creusot` · `common/company_types/joi_companies.txt:516`

## Отличия от ваниль

- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/france_schneider_et_cie.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BURGUNDY`, `STATE_NORMANDY`
- **building_types**: [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Электростанции|Электростанции]], [[vc/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_schneider_guns`
- **potential**: скрипт, строки 539–541
- **attainable**: скрипт, строки 543–549
- **possible**: скрипт, строки 551–561
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-loss-mult|unit_morale_loss_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-mult|goods_output_electricity_mult]] = `0.15` → [[vanilla/Товары/Электричество|Электричество]]
- **ai_will_do**: скрипт, строки 569–575
- **ai_construction_targets**: скрипт, строки 577–584
- **ai_weight**: скрипт, строки 586–588
