---
type: concept
description: "Вид компании «CAMECO» — T&R 1.13, `company_cameco`"
project: vic3
source: tr
aliases: ["CAMECO", "company_cameco"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_cameco
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# CAMECO

Вид компании · `company_cameco` · `common/company_types/ztr_mining_companies.txt:185`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/cameco.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NORTHWEST_TERRITORIES`, `STATE_SASKATCHEWAN`
- **building_types**: [[vanilla/Здания/Золотые рудники|Золотые рудники]], [[tr/Здания/Uranium Mines|Uranium Mines]], [[tr/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]], [[tr/Здания/Rare Earths Mines|Rare Earths Mines]]
- **potential**: скрипт, строки 205–207
- **attainable**: скрипт, строки 208–218
- **possible**: скрипт, строки 219–235
- **prosperity_modifier**:
  - `goods_input_good_uranium_mult` = `-0.05` → [[tr/Товары/Uranium|Uranium]]
  - `goods_output_good_uranium_mult` = `0.05` → [[tr/Товары/Uranium|Uranium]]
  - `state_birth_rate_mult` = `0.05`
- **ai_will_do**: скрипт, строки 241–248
- **ai_construction_targets**: скрипт, строки 249–268
- **ai_weight**: скрипт, строки 269–271
