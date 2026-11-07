---
type: concept
description: "Вид компании ««Great Indian Peninsula Railway»» — VC 1.13, `company_great_indian_railway`"
project: vic3
audience: agent
source: vc
aliases: ["«Great Indian Peninsula Railway»", "Great Indian Peninsula Railway", "company_great_indian_railway"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_great_indian_railway
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Great Indian Peninsula Railway»]]"
---
# «Great Indian Peninsula Railway»

Вид компании · `company_great_indian_railway` · `common/company_types/joi_companies.txt:1740`

## Отличия от ваниль

- **building_types**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/india_great_indian_peninsula_railway.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_railways.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vc/Здания/Железные рудники|Железные рудники]]
- **potential**: скрипт, строки 1757–1762
- **attainable**: скрипт, строки 1764–1770
- **possible**: скрипт, строки 1772–1783
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `20`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-mult|state_infrastructure_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-supply-consumption-mult|unit_supply_consumption_mult]] = `-0.1`
- **ai_will_do**: скрипт, строки 1791–1797
- **ai_construction_targets**: скрипт, строки 1799–1807
- **ai_weight**: скрипт, строки 1809–1811
