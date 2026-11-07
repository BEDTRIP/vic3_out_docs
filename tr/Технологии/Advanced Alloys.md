---
type: concept
description: "Технология «Advanced Alloys» — T&R 1.13, `advanced_alloys`"
project: vic3
source: tr
aliases: ["Advanced Alloys", "advanced_alloys"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: advanced_alloys
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_production.txt]
---
# Advanced Alloys

Технология · `advanced_alloys` · `common/technology/technologies/ztr_new_production.txt:1411`

## Поля

- **era**: `era_9`
- **texture**: `gfx/interface/icons/invention_icons/advanced_alloys.dds`
- **category**: `production`
- **unlocking_technologies**: [[tr/Технологии/Rare Earths Purification|Rare Earths Purification]], [[tr/Технологии/Continuous Casting|Continuous Casting]]
- **modifier**:
  - `goods_input_advancedores_mult` = `-0.05` → [[tr/Товары/Advanced Ores|Advanced Ores]]
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.05` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
  - `building_alloys_plant_throughput_add` = `0.1` → [[tr/Здания/Alloys Plants|Alloys Plants]]
- **ai_weight**: скрипт, строки 1424–1432
