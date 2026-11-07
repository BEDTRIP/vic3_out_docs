---
type: concept
description: "Технология «Genetics» — T&R 1.13, `dubois_genetics_tech`"
project: vic3
source: tr
aliases: ["Genetics", "dubois_genetics_tech"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: dubois_genetics_tech
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_modified_mr_society.txt]
---
# Genetics

Технология · `dubois_genetics_tech` · `common/technology/technologies/ztr_modified_mr_society.txt:102`

## Поля

- **era**: `era_4`
- **texture**: `gfx/interface/icons/invention_icons/dubois_genetics_tech.dds`
- **category**: `society`
- **modifier**:
  - `state_mortality_mult` = `-0.025`
  - `building_group_bg_agriculture_throughput_add` = `0.1`
  - `building_group_bg_ranching_throughput_add` = `0.1`
  - `building_group_bg_plantations_throughput_add` = `0.1`
  - `goods_output_grain_mult` = `0.05` → [[vanilla/Товары/Зерно|Зерно]]
  - `goods_output_fruit_mult` = `0.05` → [[vanilla/Товары/Фрукты|Фрукты]]
  - `goods_output_sugar_mult` = `0.05` → [[vanilla/Товары/Сахар|Сахар]]
- **unlocking_technologies**: [[tr/Технологии/Nature Protection|Nature Protection]]
- **ai_weight**: скрипт, строки 122–132

## Ссылаются

- **Технологии** (открывает): [[tr/Технологии/Molecular Biology|Molecular Biology]]
