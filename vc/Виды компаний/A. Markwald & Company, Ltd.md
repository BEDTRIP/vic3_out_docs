---
type: concept
description: "Вид компании «A. Markwald & Company, Ltd» — VC 1.13, `company_a_markwald_and_company`"
project: vic3
audience: agent
source: vc
aliases: ["A. Markwald & Company, Ltd", "company_a_markwald_and_company"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_a_markwald_and_company
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/A. Markwald & Company, Ltd]]"
---
# A. Markwald & Company, Ltd

Вид компании · `company_a_markwald_and_company` · `common/company_types/joi_companies.txt:8364`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **prestige_goods_trigger**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_a_markwald_and_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_rice.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BANGKOK`
- **building_types**: [[vc/Здания/Рисовые поля|Рисовые поля]], [[vanilla/Здания/Порты|Порты]], [[vc/Здания/Производства инструментов|Производства инструментов]]
- **extension_building_types**: [[vc/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: `prestige_good_generic_tools`
- **prestige_goods_trigger**: скрипт, строки 8387–8392
- **potential**: скрипт, строки 8394–8396
- **attainable**: скрипт, строки 8398–8406
- **possible**: скрипт, строки 8408–8418
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-ranching-throughput-add|building_group_bg_ranching_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-logging-throughput-add|building_group_bg_logging_throughput_add]] = `0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-mult|goods_output_grain_mult]] = `0.15` → [[vanilla/Товары/Зерно|Зерно]]
- **ai_will_do**: скрипт, строки 8426–8430
- **ai_construction_targets**: скрипт, строки 8432–8439
- **ai_weight**: скрипт, строки 8441–8443
