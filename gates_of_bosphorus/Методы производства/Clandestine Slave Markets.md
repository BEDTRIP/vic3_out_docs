---
type: concept
description: "Метод производства «Clandestine Slave Markets» — Gates of Bosphorus 1.15, `pm_gbbf_hidden_slave_markets`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Clandestine Slave Markets", "pm_gbbf_hidden_slave_markets"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_hidden_slave_markets
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Clandestine Slave Markets

Метод производства · `pm_gbbf_hidden_slave_markets` · `common/production_methods/gbbf_07_government_methods.txt:10`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/base1.dds`
- **unlocking_laws**: [[vanilla/Законы/Унаследованное рабство|Унаследованное рабство]], [[vanilla/Законы/Долговое рабство|Долговое рабство]], [[vanilla/Законы/Работорговля|Работорговля]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `200` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `300` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-slave-import-mult|state_slave_import_mult]] = `0.1`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-minting-add|country_minting_add]] = `1000`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `-0.025`
    - [[vanilla/движок/Модификаторы C#^m-country-infamy-decay-mult|country_infamy_decay_mult]] = `-0.05`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Avret Pazarları|Avret Pazarları]]
