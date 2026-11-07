---
type: concept
description: "Вид компании «Huawei» — T&R 1.13, `company_huawei`"
project: vic3
audience: agent
source: tr
aliases: ["Huawei", "company_huawei"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_huawei
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Huawei

Вид компании · `company_huawei` · `common/company_types/ztr_tech_companies.txt:612`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chinese_huawei.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_GUANGDONG`
- **building_types**: [[tr/Здания/Electronic Components Industries|Electronic Components Industries]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **extension_building_types**: [[tr/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_smartphones`
- **prestige_goods_trigger**: скрипт, строки 629–634
- **potential**: скрипт, строки 635–637
- **attainable**: скрипт, строки 638–644
- **possible**: скрипт, строки 645–655
- **prosperity_modifier**:
  - `building_rare_earths_mine_throughput_add` = `0.1` → [[tr/Здания/Rare Earths Mines|Rare Earths Mines]]
  - `building_datacenter_industry_throughput_add` = `0.1` → [[tr/Здания/Datacenters|Datacenters]]
- **ai_will_do**: скрипт, строки 660–666
- **ai_construction_targets**: скрипт, строки 667–674
- **ai_weight**: скрипт, строки 675–677
