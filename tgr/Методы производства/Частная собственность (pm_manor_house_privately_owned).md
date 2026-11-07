---
type: concept
description: "Метод производства «Частная собственность (pm_manor_house_privately_owned)» — TGR 1.13, `pm_manor_house_privately_owned`"
project: vic3
audience: agent
source: tgr
aliases: ["Частная собственность (pm_manor_house_privately_owned)", "Частная собственность", "pm_manor_house_privately_owned"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manor_house_privately_owned
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_manor_house_privately_owned)]]"
---
# Частная собственность (pm_manor_house_privately_owned)

Метод производства · `pm_manor_house_privately_owned` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:80`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/ownership_aristocrats.dds`
- **replacement_if_valid**: [[tgr/Методы производства/Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)|Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `50` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-weekly-trades-add|state_weekly_trades_add]] = `0.5`
    - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-add|state_trade_capacity_add]] = `1`
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `0.25`
