---
type: concept
description: "Вид компании «Gebrüder Thonet» — ваниль 1.15, `company_gebruder_thonet`"
project: vic3
audience: agent
source: vanilla
aliases: ["Gebrüder Thonet", "company_gebruder_thonet"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_gebruder_thonet
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Gebrüder Thonet

Вид компании · `company_gebruder_thonet` · `common/company_types/00_companies_mp1.txt:697`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_gebruder_thonet.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`
- **building_types**: [[vanilla/Здания/Мебельные фабрики|Мебельные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_bentwood_furniture`
- **potential**: скрипт, строки 717–720
- **attainable**: скрипт, строки 722–730
- **possible**: скрипт, строки 732–739
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-petty-bourgeoisie-pop-attraction-mult|interest_group_ig_petty_bourgeoisie_pop_attraction_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-furniture-manufactory-throughput-add|building_furniture_manufactory_throughput_add]] = `0.1` → [[vanilla/Здания/Мебельные фабрики|Мебельные фабрики]]
- **ai_will_do**: скрипт, строки 747–752
- **ai_construction_targets**: скрипт, строки 754–761
- **ai_weight**: скрипт, строки 763–765
