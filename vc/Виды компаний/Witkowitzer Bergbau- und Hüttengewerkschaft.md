---
type: concept
description: "Вид компании «Witkowitzer Bergbau- und Hüttengewerkschaft» — VC 1.13, `company_witkowitzer_bergbau_und_huttengewerkschaft`"
project: vic3
source: vc
aliases: ["Witkowitzer Bergbau- und Hüttengewerkschaft", "company_witkowitzer_bergbau_und_huttengewerkschaft"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_witkowitzer_bergbau_und_huttengewerkschaft
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Witkowitzer Bergbau- und Hüttengewerkschaft]]"
---
# Witkowitzer Bergbau- und Hüttengewerkschaft

Вид компании · `company_witkowitzer_bergbau_und_huttengewerkschaft` · `common/company_types/joi_companies.txt:6509`

## Отличия от ваниль

- **preferred_headquarters**: добавлено
- **building_types**: изменено
- **possible_prestige_goods**: добавлено
- **attainable**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: убрано
- **ai_construction_targets**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_witkowitzer_bergbau_und_huttengewerkschaft.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_UPPER_SILESIA`
- **building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Железные рудники|Железные рудники]], [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vc/Здания/Свинцовые рудники|Свинцовые рудники]], [[vc/Здания/Серные рудники|Серные рудники]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **potential**: скрипт, строки 6532–6535
- **attainable**: скрипт, строки 6537–6546
- **possible**: скрипт, строки 6548–6563
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.1` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.2` → [[vanilla/Здания/Электростанции|Электростанции]]
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.2` → [[vc/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_weight**: скрипт, строки 6571–6573
