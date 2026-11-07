---
type: concept
description: "Метод производства «Частная собственность (pm_financial_district_privately_owned)» — TGR 1.13, `pm_financial_district_privately_owned`"
project: vic3
source: tgr
aliases: ["Частная собственность (pm_financial_district_privately_owned)", "Частная собственность", "pm_financial_district_privately_owned"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_financial_district_privately_owned
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_financial_district_privately_owned)]]"
---
# Частная собственность (pm_financial_district_privately_owned)

Метод производства · `pm_financial_district_privately_owned` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:3`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **replacement_if_valid**: [[tgr/Методы производства/Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)|Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `50` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_shopkeepers_add` = `25` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `25` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_shopkeepers_shares_add` = `1`
- **state_modifiers**:
  - **level_scaled**:
    - `state_weekly_trades_add` = `0.5`
    - `state_trade_capacity_add` = `1`
    - `state_tax_capacity_add` = `0.25`
