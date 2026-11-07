---
type: concept
description: "Метод производства «Bimetallism Standard» — E&F 1.13, `pm_bimetallism_standard_bank_money_currency`"
project: vic3
source: ef
aliases: ["Bimetallism Standard", "pm_bimetallism_standard_bank_money_currency"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_bimetallism_standard_bank_money_currency
paths: [E&F/common/production_methods/15_ef_bank.txt]
---
# Bimetallism Standard

Метод производства · `pm_bimetallism_standard_bank_money_currency` · `common/production_methods/15_ef_bank.txt:77`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/bimetallism_standard.dds`
- **unlocking_laws**: [[ef/Законы/Bimetallism Standard|Bimetallism Standard]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `25` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **workforce_scaled**:
    - `goods_input_paper_add` = `1` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_silver_add` = `5` → [[ef/Товары/Silver|Silver]]
    - `goods_input_gold_add` = `1` → [[ef/Товары/Золото|Золото]]
    - `goods_output_bond_add` = `10` → [[ef/Товары/Bond|Bond]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_add` = `1000`

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Minting Type|Minting Type]]
