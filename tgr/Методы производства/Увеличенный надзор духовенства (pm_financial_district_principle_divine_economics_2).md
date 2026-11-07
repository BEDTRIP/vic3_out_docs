---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)» — TGR 1.13, `pm_financial_district_principle_divine_economics_2`"
project: vic3
source: tgr
aliases: ["Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)", "Increased Clergy Oversight", "pm_financial_district_principle_divine_economics_2"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_financial_district_principle_divine_economics_2
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)]]"
---
# Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)

Метод производства · `pm_financial_district_principle_divine_economics_2` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:51`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `50` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_clergymen_add` = `25` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
    - `building_employment_clerks_add` = `25` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_clergymen_shares_add` = `2`
- **state_modifiers**:
  - **level_scaled**:
    - `state_weekly_trades_add` = `0.5`
    - `state_trade_capacity_add` = `1`
    - `state_tax_capacity_add` = `0.25`

## Ссылаются

- **Методы производства** (replacement_if_valid): [[tgr/Методы производства/Частная собственность (pm_financial_district_privately_owned)|Частная собственность (pm_financial_district_privately_owned)]]
