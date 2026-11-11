---
type: concept
description: "Вид компании «Durand-Ruel Gallery» — VC 1.15, `company_durand_ruel`"
project: vic3
audience: agent
source: vc
aliases: ["Durand-Ruel Gallery", "company_durand_ruel"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_durand_ruel
paths: [VC/common/company_types/joi_companies.txt]
---
# Durand-Ruel Gallery

Вид компании · `company_durand_ruel` · `common/company_types/joi_companies.txt:7221`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/durand_ruel.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_corn.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[vanilla/Здания/Академии искусств|Академии искусств]], [[vc/Здания/Бумажные фабрики|Бумажные фабрики]]
- **extension_building_types**: [[vc/Здания/Текстильные фабрики|Текстильные фабрики]]
- **possible_prestige_goods**: `prestige_good_impressionnisme`
- **potential**: скрипт, строки 7242–7244
- **attainable**: скрипт, строки 7246–7252
- **possible**: скрипт, строки 7254–7264
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `10`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-paper-mult|goods_output_paper_mult]] = `0.1` → [[vanilla/Товары/Бумага|Бумага]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-mult|goods_output_fine_art_mult]] = `0.1` → [[vanilla/Товары/Картины|Картины]]
- **ai_will_do**: скрипт, строки 7272–7277
- **ai_construction_targets**: скрипт, строки 7279–7286
- **ai_weight**: скрипт, строки 7288–7290
