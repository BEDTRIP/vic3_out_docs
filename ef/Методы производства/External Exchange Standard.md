---
type: concept
description: "Метод производства «External Exchange Standard» — E&F 1.13, `pm_external_exchange_standard_bank_money_currency`"
project: vic3
source: ef
aliases: ["External Exchange Standard", "pm_external_exchange_standard_bank_money_currency"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_external_exchange_standard_bank_money_currency
paths: [E&F/common/production_methods/15_ef_bank.txt]
---
# External Exchange Standard

Метод производства · `pm_external_exchange_standard_bank_money_currency` · `common/production_methods/15_ef_bank.txt:163`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/external_exchange_standard.dds`
- **is_default**: `yes`
- **unlocking_laws**: [[ef/Законы/External Exchange Standard|External Exchange Standard]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `25` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `2` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-bond-add|goods_output_bond_add]] = `10` → [[ef/Товары/Bond|Bond]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-minting-add|country_minting_add]] = `1000`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Minting Type|Minting Type]]
