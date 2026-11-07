---
type: concept
description: "Вид компании «Mabe» — T&R 1.13, `company_mabe`"
project: vic3
source: tr
aliases: ["Mabe", "company_mabe"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mabe
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_furniture_companies.txt]
---
# Mabe

Вид компании · `company_mabe` · `common/company_types/ztr_furniture_companies.txt:553`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/mexican_mabe.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MEXICO`
- **building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Стеклозаводы|Стеклозаводы]]
- **potential**: скрипт, строки 564–566
- **attainable**: скрипт, строки 567–574
- **possible**: скрипт, строки 575–585
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-tooling-workshop-throughput-add|building_tooling_workshop_throughput_add]] = `0.05` → [[tr/Здания/Производства инструментов|Производства инструментов]]
- **ai_will_do**: скрипт, строки 590–596
- **ai_construction_targets**: скрипт, строки 597–604
- **ai_weight**: скрипт, строки 605–607
