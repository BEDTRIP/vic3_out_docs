---
type: concept
description: "Вид компании ««Bombay Dyeing and Manufacturing Company Limited»» — ваниль 1.13, `company_bombay_dyeing_company`"
project: vic3
source: vanilla
aliases: ["«Bombay Dyeing and Manufacturing Company Limited»", "Bombay Dyeing and Manufacturing Company Limited", "company_bombay_dyeing_company"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bombay_dyeing_company
paths: [.vanillaVIC3/common/company_types/00_companies_ip2.txt]
---
# «Bombay Dyeing and Manufacturing Company Limited»

Вид компании · `company_bombay_dyeing_company` · `common/company_types/00_companies_ip2.txt:69`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ip2_bombay_dyeing.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BOMBAY`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 89–94
- **potential**: скрипт, строки 96–99
- **attainable**: скрипт, строки 101–107
- **possible**: скрипт, строки 109–119
- **prosperity_modifier**:
  - `building_dye_plantation_throughput_add` = `0.2` → [[vanilla/Здания/Плантации красильных растений|Плантации красильных растений]]
  - `building_cotton_plantation_throughput_add` = `0.05` → [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **ai_will_do**: скрипт, строки 126–131
- **ai_construction_targets**: скрипт, строки 133–140
- **ai_weight**: скрипт, строки 142–144
