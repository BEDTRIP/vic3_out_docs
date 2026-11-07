---
type: concept
description: "Вид компании «Кооператив модов Victoria 3» — CMF 1.13, `company_vic3_mod_coop`"
project: vic3
source: cmf
aliases: ["Кооператив модов Victoria 3", "Victoria 3 Mod Co-op", "company_vic3_mod_coop"]
tags: [CMF, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_vic3_mod_coop
paths: [_cmf/common/company_types/com_companies.txt]
---
# Кооператив модов Victoria 3

Вид компании · `company_vic3_mod_coop` · `common/company_types/com_companies.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/vic3_mod_coop.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Академии искусств|Академии искусств]]
- **extension_building_types**: [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]], [[vanilla/Здания/Электрозаводы|Электрозаводы]], [[vanilla/Здания/Золотые рудники|Золотые рудники]]
- **potential**: скрипт, строки 17–33
- **attainable**: скрипт, строки 34–51
- **possible**: скрипт, строки 52–67
- **prosperity_modifier**:
  - `state_education_access_add` = `0.10`
  - `country_tech_research_speed_mult` = `0.05`
- **ai_weight**: скрипт, строки 72–74
- **ai_construction_targets**: скрипт, строки 75–82
- **ai_will_do**: скрипт, строки 83–88
