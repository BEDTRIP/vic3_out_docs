---
type: concept
description: "Метод производства «Gold Standard» — E&F 1.13, `pm_gold_standard_bank_money_currency`"
project: vic3
source: ef
aliases: ["Gold Standard", "pm_gold_standard_bank_money_currency"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gold_standard_bank_money_currency
paths: [E&F/common/production_methods/15_ef_bank.txt]
---
# Gold Standard

Метод производства · `pm_gold_standard_bank_money_currency` · `common/production_methods/15_ef_bank.txt:111`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gold_standard.dds`
- **unlocking_laws**: [[ef/Законы/Gold Standard|Gold Standard]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `25` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `1` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-gold-add|goods_input_gold_add]] = `1` → [[ef/Товары/Золото|Золото]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-bond-add|goods_output_bond_add]] = `10` → [[ef/Товары/Bond|Bond]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-minting-add|country_minting_add]] = `1000`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Minting Type|Minting Type]]
