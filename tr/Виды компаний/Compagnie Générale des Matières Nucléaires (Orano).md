---
type: concept
description: "Вид компании «Compagnie Générale des Matières Nucléaires (Orano)» — T&R 1.13, `company_compagnie_generale_des_matieres_nucleaires`"
project: vic3
source: tr
aliases: ["Compagnie Générale des Matières Nucléaires (Orano)", "company_compagnie_generale_des_matieres_nucleaires"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_compagnie_generale_des_matieres_nucleaires
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# Compagnie Générale des Matières Nucléaires (Orano)

Вид компании · `company_compagnie_generale_des_matieres_nucleaires` · `common/company_types/ztr_mining_companies.txt:275`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/orano.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`, `STATE_PROVENCE`
- **building_types**: [[tr/Здания/Uranium Mines|Uranium Mines]], [[tr/Здания/Электростанции|Электростанции]]
- **potential**: скрипт, строки 290–295
- **attainable**: скрипт, строки 296–306
- **possible**: скрипт, строки 307–320
- **prosperity_modifier**:
  - `building_power_plant_throughput_add` = `0.05` → [[tr/Здания/Электростанции|Электростанции]]
  - `goods_input_good_uranium_mult` = `-0.05` → [[tr/Товары/Uranium|Uranium]]
  - `goods_output_good_uranium_mult` = `0.05` → [[tr/Товары/Uranium|Uranium]]
- **ai_will_do**: скрипт, строки 326–335
- **ai_construction_targets**: скрипт, строки 336–340
- **ai_weight**: скрипт, строки 341–343
