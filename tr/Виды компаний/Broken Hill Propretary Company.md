---
type: concept
description: "Вид компании «Broken Hill Propretary Company» — T&R 1.13, `company_bhp`"
project: vic3
audience: agent
source: tr
aliases: ["Broken Hill Propretary Company", "company_bhp"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bhp
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# Broken Hill Propretary Company

Вид компании · `company_bhp` · `common/company_types/ztr_mining_companies.txt:9`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/bhp.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_SOUTH_WALES`, `STATE_VICTORIA`
- **building_types**: [[tr/Здания/Железные рудники|Железные рудники]], [[tr/Здания/Угольные шахты|Угольные шахты]], [[tr/Здания/Uranium Mines|Uranium Mines]]
- **extension_building_types**: [[tr/Здания/Свинцовые рудники|Свинцовые рудники]], [[tr/Здания/Common Ores Mines|Common Ores Mines]]
- **potential**: скрипт, строки 29–33
- **attainable**: скрипт, строки 34–45
- **possible**: скрипт, строки 46–61
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.05` → [[tr/Здания/Электростанции|Электростанции]]
  - [[vanilla/движок/Модификаторы B#^m-building-coal-mine-throughput-add|building_coal_mine_throughput_add]] = `0.05` → [[tr/Здания/Угольные шахты|Угольные шахты]]
  - `goods_input_good_uranium_mult` = `-0.1` → [[tr/Товары/Uranium|Uranium]]
- **ai_will_do**: скрипт, строки 67–75
- **ai_construction_targets**: скрипт, строки 76–95
- **ai_weight**: скрипт, строки 96–98
