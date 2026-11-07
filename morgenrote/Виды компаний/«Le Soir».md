---
type: concept
description: "Вид компании ««Le Soir»» — Morgenröte 1.13, `pbi_company_le_soir`"
project: vic3
source: morgenrote
aliases: ["«Le Soir»", "Le Soir", "pbi_company_le_soir"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pbi_company_le_soir
paths: [Morgenrote/common/company_types/mr_manzoni_company_types.txt]
---
# «Le Soir»

Вид компании · `pbi_company_le_soir` · `common/company_types/mr_manzoni_company_types.txt:2709`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/pbi_le_soir_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FLANDERS`
- **building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_prints`
- **prestige_goods_trigger**: скрипт, строки 2731–2736
- **potential**: скрипт, строки 2738–2742
- **attainable**: пусто
- **possible**: скрипт, строки 2747–2757
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-pop-attraction-mult|interest_group_ig_intelligentsia_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 2764–2769
- **ai_construction_targets**: скрипт, строки 2771–2778
- **ai_weight**: скрипт, строки 2780–2782
