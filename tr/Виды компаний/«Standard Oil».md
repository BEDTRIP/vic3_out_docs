---
type: concept
description: "Вид компании ««Standard Oil»» — T&R 1.13, `company_standard_oil`"
project: vic3
audience: agent
source: tr
aliases: ["«Standard Oil»", "Standard Oil", "company_standard_oil"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_standard_oil
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_usa.txt]
replaces: "[[vanilla/Виды компаний/«Standard Oil»]]"
---
# «Standard Oil»

Вид компании · `company_standard_oil` · `common/company_types/ztr_companies_usa.txt:2` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **building_types**: вставка в блок
- **extension_building_types**: вставка в блок
- **prosperity_modifier**: вставка в блок

## Поля

- **building_types**: [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]], [[tr/Здания/Oil Refineries|Oil Refineries]]
- **extension_building_types**: [[tr/Здания/Petrochemical Industries|Petrochemical Industries]]
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `-0.2` → [[tr/Здания/Железные дороги|Железные дороги]]
  - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.1`
  - `building_natural_gas_rig_throughput_add` = `0.15` → [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
