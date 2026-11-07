---
type: concept
description: "Технология «Natural Gas Extraction» — T&R 1.13, `natural_gas_extraction`"
project: vic3
audience: agent
source: tr
aliases: ["Natural Gas Extraction", "natural_gas_extraction"]
tags: [tr, технология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: natural_gas_extraction
paths: [TechRes+Kuromi/t&r/common/technology/technologies/ztr_new_production.txt]
---
# Natural Gas Extraction

Технология · `natural_gas_extraction` · `common/technology/technologies/ztr_new_production.txt:228`

## Поля

- **era**: `era_5`
- **texture**: `gfx/interface/icons/invention_icons/natural_gas_extraction.dds`
- **category**: `production`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]], [[tr/Технологии/Geothermal Energy|Geothermal Energy]]
- **modifier**:
  - `country_allow_everywhere_gas_extraction_bool` = `yes`
  - `building_natural_gas_rig_throughput_add` = `0.05` → [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.05`
- **ai_weight**: скрипт, строки 242–253

## Ссылаются

- **Здания** (открывает): [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
- **Методы производства** (открывает): [[tr/Методы производства/Gas Steam Derrick|Gas Steam Derrick]], [[tr/Методы производства/HB Process - Steam Reforming|HB Process - Steam Reforming]]
- **Технологии** (открывает): [[tr/Технологии/Gas Turbine|Gas Turbine]], [[tr/Технологии/Sponge Iron|Sponge Iron]]
