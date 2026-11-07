---
type: concept
description: "Вид компании «Noda Shoyu Co. Ltd» — VC 1.13, `company_noda_shoyu`"
project: vic3
audience: agent
source: vc
aliases: ["Noda Shoyu Co. Ltd", "company_noda_shoyu"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_noda_shoyu
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Noda Shoyu Co. Ltd]]"
---
# Noda Shoyu Co. Ltd

Вид компании · `company_noda_shoyu` · `common/company_types/joi_companies.txt:8124`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_noda_shoyu.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rice.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]], [[vc/Здания/Рисовые поля|Рисовые поля]]
- **extension_building_types**: [[vc/Здания/Виноградники|Виноградники]]
- **possible_prestige_goods**: `prestige_good_kikkoman_soy_sauce`
- **potential**: скрипт, строки 8145–8148
- **attainable**: скрипт, строки 8150–8158
- **possible**: скрипт, строки 8160–8170
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `0.25`
- **ai_will_do**: скрипт, строки 8178–8182
- **ai_construction_targets**: скрипт, строки 8184–8191
- **ai_weight**: скрипт, строки 8193–8195
