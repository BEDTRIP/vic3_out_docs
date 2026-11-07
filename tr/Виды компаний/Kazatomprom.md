---
type: concept
description: "Вид компании «Kazatomprom» — T&R 1.13, `company_kazatomprom`"
project: vic3
audience: agent
source: tr
aliases: ["Kazatomprom", "company_kazatomprom"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_kazatomprom
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# Kazatomprom

Вид компании · `company_kazatomprom` · `common/company_types/ztr_mining_companies.txt:347`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/kazak_kazatomprom.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KIRGHIZIA`, `STATE_SEMIRECHE`, `STATE_AKMOLINSK`
- **building_types**: [[tr/Здания/Uranium Mines|Uranium Mines]], [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]]
- **extension_building_types**: [[tr/Здания/Rare Earths Mines|Rare Earths Mines]]
- **potential**: скрипт, строки 366–368
- **attainable**: скрипт, строки 369–380
- **possible**: скрипт, строки 381–398
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.05` → [[tr/Здания/Электростанции|Электростанции]]
  - `goods_output_good_uranium_mult` = `0.1` → [[tr/Товары/Uranium|Uranium]]
- **ai_will_do**: скрипт, строки 403–413
- **ai_construction_targets**: скрипт, строки 414–435
- **ai_weight**: скрипт, строки 436–438
