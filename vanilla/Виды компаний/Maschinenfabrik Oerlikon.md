---
type: concept
description: "Вид компании «Maschinenfabrik Oerlikon» — ваниль 1.13, `company_maschinenfabrik_oerlikon`"
project: vic3
source: vanilla
aliases: ["Maschinenfabrik Oerlikon", "company_maschinenfabrik_oerlikon"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_maschinenfabrik_oerlikon
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Maschinenfabrik Oerlikon

Вид компании · `company_maschinenfabrik_oerlikon` · `common/company_types/00_companies_ep2.txt:942`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_maschinenfabrik_oerlikon.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EAST_SWITZERLAND`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_oerlikon_engines`
- **potential**: скрипт, строки 965–968
- **attainable**: скрипт, строки 970–978
- **possible**: скрипт, строки 980–990
- **prosperity_modifier**:
  - `building_railway_throughput_add` = `0.1` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - `country_weekly_innovation_mult` = `0.05`
- **ai_will_do**: скрипт, строки 997–1001
- **ai_construction_targets**: скрипт, строки 1003–1010
- **ai_weight**: скрипт, строки 1012–1014
