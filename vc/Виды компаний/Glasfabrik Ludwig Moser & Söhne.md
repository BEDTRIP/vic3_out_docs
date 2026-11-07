---
type: concept
description: "Вид компании «Glasfabrik Ludwig Moser & Söhne» — VC 1.13, `company_ludwig_moser_and_sons`"
project: vic3
audience: agent
source: vc
aliases: ["Glasfabrik Ludwig Moser & Söhne", "company_ludwig_moser_and_sons"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ludwig_moser_and_sons
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Glasfabrik Ludwig Moser & Söhne]]"
---
# Glasfabrik Ludwig Moser & Söhne

Вид компании · `company_ludwig_moser_and_sons` · `common/company_types/joi_companies.txt:4270`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **attainable**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_ludwig_moser_and_sons.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BOHEMIA`
- **building_types**: [[vc/Здания/Стеклозаводы|Стеклозаводы]], [[vc/Здания/Свинцовые рудники|Свинцовые рудники]]
- **extension_building_types**: [[vc/Здания/Мебельные фабрики|Мебельные фабрики]]
- **potential**: скрипт, строки 4287–4290
- **possible_prestige_goods**: `prestige_good_bohemian_crystal`
- **attainable**: пусто
- **possible**: скрипт, строки 4299–4308
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-glass-mult|goods_output_glass_mult]] = `0.15` → [[vanilla/Товары/Стекло|Стекло]]
  - [[vanilla/движок/Модификаторы C#^m-country-leverage-generation-mult|country_leverage_generation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 4316–4321
- **ai_construction_targets**: скрипт, строки 4323–4330
- **ai_weight**: скрипт, строки 4332–4334
