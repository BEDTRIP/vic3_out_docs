---
type: explanation
description: "Вид компании «Oesterreichisch-Alpine Montangesellschaft» — ваниль 1.15.2, `company_oesterreichisch_alpine_montangesellschaft`"
project: vic3
audience: agent
source: vanilla
aliases: ["Oesterreichisch-Alpine Montangesellschaft", "company_oesterreichisch_alpine_montangesellschaft"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_oesterreichisch_alpine_montangesellschaft
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Oesterreichisch-Alpine Montangesellschaft

Вид компании · `company_oesterreichisch_alpine_montangesellschaft` · `common/company_types/00_companies_ip3.txt:563`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_oesterreichisch_alpine_montangesellschaft.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **potential**: скрипт, строки 578–580
- **attainable**: скрипт, строки 582–590
- **possible**: скрипт, строки 592–604
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-coal-mine-throughput-add|building_coal_mine_throughput_add]] = `0.1` → [[vanilla/Здания/Угольные шахты|Угольные шахты]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.05` → [[vanilla/Здания/Железные дороги|Железные дороги]]
- **ai_will_do**: скрипт, строки 611–616
- **ai_construction_targets**: скрипт, строки 618–631
- **ai_weight**: скрипт, строки 633–635
