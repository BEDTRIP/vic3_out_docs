---
type: concept
description: "Вид компании «Taiping Tea & Grain» — TGR 1.15, `company_ong_lung_sheng_tea_company_heaven_kingdom`"
project: vic3
audience: agent
source: tgr
aliases: ["Taiping Tea & Grain", "company_ong_lung_sheng_tea_company_heaven_kingdom"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ong_lung_sheng_tea_company_heaven_kingdom
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
---
# Taiping Tea & Grain

Вид компании · `company_ong_lung_sheng_tea_company_heaven_kingdom` · `common/company_types/TGR_TRADE_companies.txt:1522`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_lanfang_kongsi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ZHEJIANG`
- **building_types**: [[vanilla/Здания/Чайные плантации|Чайные плантации]], [[vanilla/Здания/Рисовые поля|Рисовые поля]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_generic_grain`, `prestige_good_china_tea`
- **potential**: скрипт, строки 1545–1548
- **attainable**: пусто
- **possible**: скрипт, строки 1553–1562
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-add|state_infrastructure_from_population_add]] = `1`
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-max-add|state_infrastructure_from_population_max_add]] = `50`
- **ai_will_do**: скрипт, строки 1569–1571
- **ai_construction_targets**: скрипт, строки 1573–1592
- **ai_weight**: скрипт, строки 1594–1596
