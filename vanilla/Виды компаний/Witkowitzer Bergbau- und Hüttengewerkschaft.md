---
type: concept
description: "Вид компании «Witkowitzer Bergbau- und Hüttengewerkschaft» — ваниль 1.15, `company_witkowitzer_bergbau_und_huttengewerkschaft`"
project: vic3
audience: agent
source: vanilla
aliases: ["Witkowitzer Bergbau- und Hüttengewerkschaft", "company_witkowitzer_bergbau_und_huttengewerkschaft"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_witkowitzer_bergbau_und_huttengewerkschaft
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Witkowitzer Bergbau- und Hüttengewerkschaft

Вид компании · `company_witkowitzer_bergbau_und_huttengewerkschaft` · `common/company_types/00_companies_ip3.txt:482`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_witkowitzer_bergbau_und_huttengewerkschaft.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]], [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Медные рудники|Медные рудники]]
- **potential**: скрипт, строки 499–502
- **attainable**: скрипт, строки 504–510
- **possible**: скрипт, строки 512–524
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-construction-sector-throughput-add|building_construction_sector_throughput_add]] = `0.05` → [[vanilla/Здания/Строительные сектора|Строительные сектора]]
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.1` → [[vanilla/Здания/Электростанции|Электростанции]]
- **ai_will_do**: скрипт, строки 531–536
- **ai_construction_targets**: скрипт, строки 538–551
- **ai_weight**: скрипт, строки 553–555
