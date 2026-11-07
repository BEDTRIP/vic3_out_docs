---
type: concept
description: "Вид компании ««Klabin Irmãos & Cia.»» — VC 1.13, `company_kablin`"
project: vic3
audience: agent
source: vc
aliases: ["«Klabin Irmãos & Cia.»", "Klabin Irmãos & Cia", "company_kablin"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_kablin
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«Klabin Irmãos & Cia.»]]"
---
# «Klabin Irmãos & Cia.»

Вид компании · `company_kablin` · `common/company_types/joi_companies.txt:7693`

## Отличия от ваниль

- **category**: добавлено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/brazil_kablin_irmaos_and_cia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **category**: `aristocrat_owned`
- **flavored_company**: `yes`
- **building_types**: [[vc/Здания/Бумажные фабрики|Бумажные фабрики]], [[vc/Здания/Лесозаготовки|Лесозаготовки]], [[vc/Здания/Серные рудники|Серные рудники]]
- **extension_building_types**: [[vc/Здания/Каучуковые плантации|Каучуковые плантации]]
- **possible_prestige_goods**: `prestige_good_rosewood`
- **potential**: скрипт, строки 7715–7717
- **attainable**: скрипт, строки 7719–7725
- **possible**: скрипт, строки 7727–7738
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-wood-mult|goods_output_wood_mult]] = `0.1` → [[vanilla/Товары/Древесина|Древесина]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-hardwood-mult|goods_output_hardwood_mult]] = `0.1` → [[vanilla/Товары/Твёрдая древесина|Твёрдая древесина]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-logging-employee-mult|building_group_bg_logging_employee_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 7746–7752
- **ai_construction_targets**: скрипт, строки 7754–7762
- **ai_weight**: скрипт, строки 7764–7766
