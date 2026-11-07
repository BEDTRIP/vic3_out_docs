---
type: concept
description: "Вид компании «Companhia União Fabril» — ваниль 1.13, `company_uniao_fabril`"
project: vic3
source: vanilla
aliases: ["Companhia União Fabril", "company_uniao_fabril"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_uniao_fabril
paths: [.vanillaVIC3/common/company_types/00_companies_ip4.txt]
---
# Companhia União Fabril

Вид компании · `company_uniao_fabril` · `common/company_types/00_companies_ip4.txt:536`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_companhia_uniao_fabril.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]], [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Табачные плантации|Табачные плантации]]
- **extension_building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]], [[vanilla/Здания/Порты|Порты]], [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **possible_prestige_goods**: `prestige_good_generic_fertilizer`
- **prestige_goods_trigger**: скрипт, строки 559–564
- **potential**: скрипт, строки 566–569
- **attainable**: скрипт, строки 571–579
- **possible**: скрипт, строки 581–597
- **prosperity_modifier**:
  - `country_production_tech_research_speed_mult` = `0.1`
  - `state_radicals_from_political_movements_mult` = `-0.05`
- **ai_will_do**: скрипт, строки 604–611
- **ai_construction_targets**: скрипт, строки 613–641
- **ai_weight**: скрипт, строки 643–645
