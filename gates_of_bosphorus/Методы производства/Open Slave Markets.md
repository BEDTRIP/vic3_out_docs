---
type: concept
description: "Метод производства «Open Slave Markets» — Gates of Bosphorus 1.13, `pm_gbbf_open_slave_markets`"
project: vic3
source: gates_of_bosphorus
aliases: ["Open Slave Markets", "pm_gbbf_open_slave_markets"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_open_slave_markets
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Open Slave Markets

Метод производства · `pm_gbbf_open_slave_markets` · `common/production_methods/gbbf_07_government_methods.txt:39`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/base1.dds`
- **unlocking_laws**: [[vanilla/Законы/Долговое рабство|Долговое рабство]], [[vanilla/Законы/Работорговля|Работорговля]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_aristocrats_add` = `300` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_bureaucrats_add` = `700` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_slaves_add` = `3000` → [[vanilla/Население/Типы/Рабы|Рабы]]
  - **workforce_scaled**:
    - `state_slave_import_mult` = `0.1`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_slave_import_mult` = `0.25`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_add` = `2500`
    - `country_prestige_mult` = `-0.05`
    - `country_infamy_decay_mult` = `-0.10`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Avret Pazarları|Avret Pazarları]]
