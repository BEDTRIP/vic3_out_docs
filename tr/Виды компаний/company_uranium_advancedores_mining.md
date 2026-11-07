---
type: concept
description: "Вид компании «company_uranium_advancedores_mining» — T&R 1.13, `company_uranium_advancedores_mining`"
project: vic3
audience: agent
source: tr
aliases: ["company_uranium_advancedores_mining"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_uranium_advancedores_mining
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_99_basic_companies.txt]
---
# company_uranium_advancedores_mining

Вид компании · `company_uranium_advancedores_mining` · `common/company_types/ztr_99_basic_companies.txt:244`

## Поля

- **icon**: `gfx/interface/icons/company_icons/uranium_advancedores_mining.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `no`
- **uses_dynamic_naming**: `yes`
- **dynamic_company_type_names**: `dynamic_company_type_company`, `dynamic_company_type_consortium`, `dynamic_company_type_corporation`, `dynamic_company_type_conglomerate`, `dynamic_company_type_syndicate`, `dynamic_company_type_combine`, `dynamic_company_type_guild`
- **building_types**: [[tr/Здания/Uranium Mines|Uranium Mines]], [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]]
- **extension_building_types**: [[tr/Здания/Rare Earths Mines|Rare Earths Mines]], [[tr/Здания/Электростанции|Электростанции]]
- **possible**: скрипт, строки 273–284
- **prosperity_modifier**:
  - `goods_input_good_uranium_mult` = `-0.1` → [[tr/Товары/Uranium|Uranium]]
  - `building_battery_plant_throughput_add` = `0.1` → [[tr/Здания/Battery Plants|Battery Plants]]
- **ai_will_do**: скрипт, строки 291–302
