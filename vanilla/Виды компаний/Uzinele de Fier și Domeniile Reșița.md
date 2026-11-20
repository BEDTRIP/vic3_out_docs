---
type: explanation
description: "Вид компании «Uzinele de Fier și Domeniile Reșița» — ваниль 1.15.2, `company_resita_works`"
project: vic3
audience: agent
source: vanilla
aliases: ["Uzinele de Fier și Domeniile Reșița", "company_resita_works"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_resita_works
paths: [.vanillaVIC3/common/company_types/00_companies_ip5.txt]
---
# Uzinele de Fier și Domeniile Reșița

Вид компании · `company_resita_works` · `common/company_types/00_companies_ip5.txt:619`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_uzinele_de_fier_si_domeniile_resita.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BANAT`
- **building_types**: [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 642–647
- **potential**: скрипт, строки 649–651
- **attainable**: скрипт, строки 653–659
- **possible**: скрипт, строки 661–672
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `0.1` → [[vanilla/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы B#^m-building-artillery-foundry-throughput-add|building_artillery_foundry_throughput_add]] = `0.1` → [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **ai_will_do**: скрипт, строки 679–684
- **ai_construction_targets**: скрипт, строки 686–693
- **ai_weight**: скрипт, строки 695–697
