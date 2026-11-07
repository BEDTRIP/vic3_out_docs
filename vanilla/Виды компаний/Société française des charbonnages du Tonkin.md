---
type: concept
description: "Вид компании «Société française des charbonnages du Tonkin» — ваниль 1.13, `company_societe_francaise_charbonnages_du_tonkin`"
project: vic3
source: vanilla
aliases: ["Société française des charbonnages du Tonkin", "company_societe_francaise_charbonnages_du_tonkin"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_societe_francaise_charbonnages_du_tonkin
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Société française des charbonnages du Tonkin

Вид компании · `company_societe_francaise_charbonnages_du_tonkin` · `common/company_types/00_companies_ep2.txt:378`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_societe_francaise_charbonnages_du_tonkin.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_TONKIN`
- **building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **extension_building_types**: [[vanilla/Здания/Порты|Порты]], [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 403–405
- **attainable**: скрипт, строки 407–415
- **possible**: скрипт, строки 417–427
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-coal-mine-throughput-add|building_coal_mine_throughput_add]] = `0.1` → [[vanilla/Здания/Угольные шахты|Угольные шахты]]
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-mult|country_bureaucracy_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 434–439
- **ai_construction_targets**: скрипт, строки 441–448
- **ai_weight**: скрипт, строки 450–452
