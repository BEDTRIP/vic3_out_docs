---
type: concept
description: "Вид компании «Changyu» — Mandate of Heaven 1.15, `company_changyu`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Changyu", "company_changyu"]
tags: [mandate_of_heaven, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_changyu
paths: [for addon/Mandate of Heaven/common/company_types/moh_companies_china.txt]
---
# Changyu

Вид компании · `company_changyu` · `common/company_types/moh_companies_china.txt:300`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/changyu.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_corn.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Виноградники|Виноградники]]
- **extension_building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **preferred_headquarters**: `STATE_SHANDONG`
- **potential**: скрипт, строки 311–313
- **attainable**: скрипт, строки 314–320
- **possible**: скрипт, строки 321–329
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-vineyard-throughput-add|building_vineyard_throughput_add]] = `0.1` → [[vanilla/Здания/Виноградники|Виноградники]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **ai_weight**: скрипт, строки 334–336
- **ai_construction_targets**: скрипт, строки 337–345
- **ai_will_do**: скрипт, строки 346–352
