---
type: concept
description: "Вид компании «Lee Wilson & Company» — VC 1.13, `company_lee_wilson`"
project: vic3
source: vc
aliases: ["Lee Wilson & Company", "company_lee_wilson"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lee_wilson
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Lee Wilson & Company]]"
---
# Lee Wilson & Company

Вид компании · `company_lee_wilson` · `common/company_types/joi_companies.txt:4338`

## Отличия от ваниль

- **attainable**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_lee_wilson.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ARKANSAS`
- **building_types**: [[vc/Здания/Плантации хлопка|Плантации хлопка]], [[vc/Здания/Лесозаготовки|Лесозаготовки]], [[vc/Здания/Пшеничные поля|Пшеничные поля]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: `prestige_good_sea_island_cotton`
- **potential**: скрипт, строки 4360–4363
- **attainable**: пусто
- **possible**: скрипт, строки 4368–4380
- **prosperity_modifier**:
  - `building_power_plant_throughput_add` = `0.1` → [[vanilla/Здания/Электростанции|Электростанции]]
  - `building_group_bg_logging_throughput_add` = `0.1`
  - `goods_output_fabric_mult` = `0.15` → [[vanilla/Товары/Ткань|Ткань]]
- **ai_will_do**: скрипт, строки 4388–4393
- **ai_construction_targets**: скрипт, строки 4395–4408
- **ai_weight**: скрипт, строки 4410–4412
