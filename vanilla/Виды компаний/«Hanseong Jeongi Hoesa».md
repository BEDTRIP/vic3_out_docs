---
type: concept
description: "Вид компании ««Hanseong Jeongi Hoesa»» — ваниль 1.15, `company_hanseong_jeongi_hoesa`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Hanseong Jeongi Hoesa»", "Hanseong Jeongi Hoesa", "company_hanseong_jeongi_hoesa"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_hanseong_jeongi_hoesa
paths: [.vanillaVIC3/common/company_types/00_companies_soi.txt]
---
# «Hanseong Jeongi Hoesa»

Вид компании · `company_hanseong_jeongi_hoesa` · `common/company_types/00_companies_soi.txt:595`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/hanseong_jeongi_hoesa.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SEOUL`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **potential**: скрипт, строки 613–616
- **attainable**: скрипт, строки 618–624
- **possible**: скрипт, строки 626–634
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-art-academy-throughput-add|building_art_academy_throughput_add]] = `0.05` → [[vanilla/Здания/Академии искусств|Академии искусств]]
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.05` → [[vanilla/Здания/Железные дороги|Железные дороги]]
- **ai_will_do**: скрипт, строки 641–647
- **ai_construction_targets**: скрипт, строки 649–656
- **ai_weight**: скрипт, строки 658–660
