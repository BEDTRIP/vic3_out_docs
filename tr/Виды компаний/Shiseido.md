---
type: concept
description: "Вид компании «Shiseido» — T&R 1.13, `company_shiseido`"
project: vic3
audience: agent
source: tr
aliases: ["Shiseido", "company_shiseido"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_shiseido
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_cosmetics_companies.txt]
---
# Shiseido

Вид компании · `company_shiseido` · `common/company_types/ztr_cosmetics_companies.txt:83`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_shiseido.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Заводы синтетики|Заводы синтетики]], [[tr/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]], [[tr/Здания/Pharmaceuticals Industries|Pharmaceuticals Industries]]
- **possible_prestige_goods**: `prestige_good_cosmetics`
- **prestige_goods_trigger**: скрипт, строки 101–106
- **potential**: скрипт, строки 107–109
- **attainable**: скрипт, строки 110–117
- **possible**: скрипт, строки 118–128
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.5`
  - `building_elgar_opera_throughput_add` = `0.05` → [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **ai_will_do**: скрипт, строки 133–139
- **ai_construction_targets**: скрипт, строки 140–147
- **ai_weight**: скрипт, строки 148–150
