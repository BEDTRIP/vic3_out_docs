---
type: concept
description: "Вид компании «Quality Grains Inc» — ваниль 1.13, `company_basic_agriculture_1`"
project: vic3
audience: agent
source: vanilla
aliases: ["Quality Grains Inc", "company_basic_agriculture_1"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_basic_agriculture_1
paths: [.vanillaVIC3/common/company_types/99_basic_companies.txt]
---
# Quality Grains Inc

Вид компании · `company_basic_agriculture_1` · `common/company_types/99_basic_companies.txt:1`

## Поля

- **icon**: `gfx/interface/icons/company_icons/company_basic_agriculture_1.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `no`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_consortium`, `dynamic_company_type_guild`, `dynamic_company_type_society`, `dynamic_company_type_fellowship`
- **building_types**: [[vanilla/Здания/Пшеничные поля|Пшеничные поля]], [[vanilla/Здания/Ржаные поля|Ржаные поля]]
- **extension_building_types**: [[vanilla/Здания/Маисовые поля|Маисовые поля]]
- **possible_prestige_goods**: `prestige_good_generic_grain`
- **prestige_goods_trigger**: скрипт, строки 32–37
- **possible**: скрипт, строки 39–49
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-livestock-ranch-throughput-add|building_livestock_ranch_throughput_add]] = `0.1` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
- **ai_will_do**: скрипт, строки 55–65
