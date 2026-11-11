---
type: concept
description: "Вид компании «Colt's Patent Firearms Manufacturing Company» — VC 1.15, `company_colt_firearms`"
project: vic3
audience: agent
source: vc
aliases: ["Colt's Patent Firearms Manufacturing Company", "company_colt_firearms"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_colt_firearms
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Colt's Patent Firearms Manufacturing Company]]"
---
# Colt's Patent Firearms Manufacturing Company

Вид компании · `company_colt_firearms` · `common/company_types/joi_companies.txt:4892`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_colt_firearms.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CONNECTICUT`
- **building_types**: [[vc/Здания/Оружейные заводы|Оружейные заводы]], [[vc/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vc/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vc/Здания/Мебельные фабрики|Мебельные фабрики]]
- **possible_prestige_goods**: `prestige_good_colt_revolvers`
- **potential**: скрипт, строки 4914–4917
- **attainable**: скрипт, строки 4919–4927
- **possible**: скрипт, строки 4929–4938
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-small-arms-mult|goods_output_small_arms_mult]] = `0.1` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
  - [[vanilla/движок/Модификаторы U#^m-unit-army-offense-mult|unit_army_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-damage-mult|unit_morale_damage_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 4946–4951
- **ai_construction_targets**: скрипт, строки 4953–4960
- **ai_weight**: скрипт, строки 4962–4964
