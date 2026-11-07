---
type: concept
description: "Вид компании «Gebrüder Thonet» — TGR 1.13, `company_gebruder_thonet`"
project: vic3
source: tgr
aliases: ["Gebrüder Thonet", "company_gebruder_thonet"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_gebruder_thonet
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/Gebrüder Thonet]]"
---
# Gebrüder Thonet

Вид компании · `company_gebruder_thonet` · `common/company_types/TGR_TRADE_companies.txt:599`

## Отличия от ваниль

- **background**: `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_…` → `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds"`
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **attainable**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_gebruder_thonet.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`
- **building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]], [[vanilla/Здания/Ржаные поля|Ржаные поля]], [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_generic_grain`
- **potential**: скрипт, строки 623–625
- **attainable**: пусто
- **possible**: скрипт, строки 630–639
- **prosperity_modifier**:
  - `interest_group_ig_petty_bourgeoisie_pop_attraction_mult` = `0.05`
  - `state_radicals_from_political_movements_mult` = `-0.05`
  - `building_furniture_manufactory_throughput_add` = `0.1` → [[tgr/Здания/Мебельные фабрики|Мебельные фабрики]]
- **ai_will_do**: скрипт, строки 647–652
- **ai_construction_targets**: скрипт, строки 654–661
- **ai_weight**: скрипт, строки 663–665
