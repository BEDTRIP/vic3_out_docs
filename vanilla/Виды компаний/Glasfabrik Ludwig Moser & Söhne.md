---
type: concept
description: "Вид компании «Glasfabrik Ludwig Moser & Söhne» — ваниль 1.13, `company_ludwig_moser_and_sons`"
project: vic3
audience: agent
source: vanilla
aliases: ["Glasfabrik Ludwig Moser & Söhne", "company_ludwig_moser_and_sons"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ludwig_moser_and_sons
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Glasfabrik Ludwig Moser & Söhne

Вид компании · `company_ludwig_moser_and_sons` · `common/company_types/00_companies_mp1.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_ludwig_moser_and_sons.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BOHEMIA`
- **building_types**: [[vanilla/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **potential**: скрипт, строки 18–21
- **possible_prestige_goods**: `prestige_good_bohemian_crystal`
- **attainable**: скрипт, строки 27–35
- **possible**: скрипт, строки 37–46
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-art-academy-throughput-add|building_art_academy_throughput_add]] = `0.05` → [[vanilla/Здания/Академии искусств|Академии искусств]]
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 54–59
- **ai_construction_targets**: скрипт, строки 61–68
- **ai_weight**: скрипт, строки 70–72
