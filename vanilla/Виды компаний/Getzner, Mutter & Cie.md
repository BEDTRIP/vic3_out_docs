---
type: concept
description: "Вид компании «Getzner, Mutter & Cie» — ваниль 1.13, `company_getzner_mutter`"
project: vic3
source: vanilla
aliases: ["Getzner, Mutter & Cie", "company_getzner_mutter"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_getzner_mutter
paths: [.vanillaVIC3/common/company_types/00_companies_ip3.txt]
---
# Getzner, Mutter & Cie

Вид компании · `company_getzner_mutter` · `common/company_types/00_companies_ip3.txt:620`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_getzner_mutter.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **potential**: скрипт, строки 639–642
- **attainable**: скрипт, строки 644–652
- **possible**: скрипт, строки 654–666
- **prosperity_modifier**:
  - `building_synthetics_plant_throughput_add` = `0.1` → [[vanilla/Здания/Заводы синтетики|Заводы синтетики]]
  - `interest_group_ig_petty_bourgeoisie_approval_add` = `2`
- **ai_will_do**: скрипт, строки 673–678
- **ai_construction_targets**: скрипт, строки 680–693
- **ai_weight**: скрипт, строки 695–697
