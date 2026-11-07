---
type: concept
description: "Метод производства «Bonds Exchange» — E&F 1.13, `pm_bond_exchange`"
project: vic3
audience: agent
source: ef
aliases: ["Bonds Exchange", "pm_bond_exchange"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_bond_exchange
paths: [E&F/common/production_methods/16_ef_financial_centre.txt]
---
# Bonds Exchange

Метод производства · `pm_bond_exchange` · `common/production_methods/16_ef_financial_centre.txt:38`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/bond_exchange.dds`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `25` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `25` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-shopkeepers-shares-add|building_shopkeepers_shares_add]] = `5`
    - [[vanilla/движок/Модификаторы B#^m-building-clerks-shares-add|building_clerks_shares_add]] = `1`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-mutual-funds-add|goods_output_mutual_funds_add]] = `1` → [[ef/Товары/Паевые инвестиционные фонды|Паевые инвестиционные фонды]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-bond-add|goods_input_bond_add]] = `1` → [[ef/Товары/Bond|Bond]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Bond Stock|Bond Stock]]
