---
type: concept
description: "Вид компании ««Diário de Notícias»» — Morgenröte 1.13, `pbi_company_diario_de_noticias`"
project: vic3
source: morgenrote
aliases: ["«Diário de Notícias»", "Diário de Notícias", "pbi_company_diario_de_noticias"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pbi_company_diario_de_noticias
paths: [Morgenrote/common/company_types/mr_manzoni_company_types.txt]
---
# «Diário de Notícias»

Вид компании · `pbi_company_diario_de_noticias` · `common/company_types/mr_manzoni_company_types.txt:2632`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/pbi_diario_de_noticias_logo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ESTREMADURA`
- **building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_prints`
- **prestige_goods_trigger**: скрипт, строки 2654–2659
- **potential**: скрипт, строки 2661–2665
- **attainable**: пусто
- **possible**: скрипт, строки 2670–2680
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-pop-attraction-mult|interest_group_ig_intelligentsia_pop_attraction_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 2687–2692
- **ai_construction_targets**: скрипт, строки 2694–2701
- **ai_weight**: скрипт, строки 2703–2705
