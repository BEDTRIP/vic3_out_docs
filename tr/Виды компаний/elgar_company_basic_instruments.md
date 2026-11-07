---
type: concept
description: "Вид компании «elgar_company_basic_instruments» — T&R 1.13, `elgar_company_basic_instruments`"
project: vic3
source: tr
aliases: ["elgar_company_basic_instruments"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_basic_instruments
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# elgar_company_basic_instruments

Вид компании · `elgar_company_basic_instruments` · `common/company_types/ztr_99_basic_companies.txt:192`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_generic.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_syndicate`, `dynamic_company_type_corporation`
- **building_types**: [[tr/Здания/Instrument Workshops|Instrument Workshops]]
- **extension_building_types**: [[tr/Здания/Производства инструментов|Производства инструментов]], [[tr/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **prestige_goods_trigger**: скрипт, строки 211–216
- **possible**: скрипт, строки 217–227
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.05` → [[tr/Товары/Instruments|Instruments]]
  - `goods_output_elgar_music_mult` = `0.05` → [[tr/Товары/Entertainment|Entertainment]]
- **ai_will_do**: скрипт, строки 232–240
