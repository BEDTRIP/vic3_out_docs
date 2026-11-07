---
type: concept
description: "Метод производства «Gold Exchange Standard» — E&F 1.13, `pm_gold_exchange_standard_bank_money_currency`"
project: vic3
source: ef
aliases: ["Gold Exchange Standard", "pm_gold_exchange_standard_bank_money_currency"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gold_exchange_standard_bank_money_currency
paths: [E&F/common/production_methods/15_ef_bank.txt]
---
# Gold Exchange Standard

Метод производства · `pm_gold_exchange_standard_bank_money_currency` · `common/production_methods/15_ef_bank.txt:138`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gold_exchange_standard.dds`
- **is_default**: `yes`
- **unlocking_laws**: [[ef/Законы/Gold exchange Standard|Gold exchange Standard]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `25` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **workforce_scaled**:
    - `goods_input_paper_add` = `2` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_bond_add` = `10` → [[ef/Товары/Bond|Bond]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_add` = `2500`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Minting Type|Minting Type]]
