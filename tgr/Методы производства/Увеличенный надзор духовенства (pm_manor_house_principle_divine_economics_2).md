---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)» — TGR 1.13, `pm_manor_house_principle_divine_economics_2`"
project: vic3
source: tgr
aliases: ["Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)", "Increased Clergy Oversight", "pm_manor_house_principle_divine_economics_2"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manor_house_principle_divine_economics_2
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_investors.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)]]"
---
# Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)

Метод производства · `pm_manor_house_principle_divine_economics_2` · `common/production_methods/TGR_TRADE_private_infrastructure_investors.txt:101`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `50` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `50` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-clergymen-shares-add|building_clergymen_shares_add]] = `1`
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-weekly-trades-add|state_weekly_trades_add]] = `0.5`
    - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-add|state_trade_capacity_add]] = `1`
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `0.25`

## Ссылаются

- **Методы производства** (replacement_if_valid): [[tgr/Методы производства/Частная собственность (pm_manor_house_privately_owned)|Частная собственность (pm_manor_house_privately_owned)]]
