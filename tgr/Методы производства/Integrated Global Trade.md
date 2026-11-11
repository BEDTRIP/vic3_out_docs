---
type: concept
description: "Метод производства «Integrated Global Trade» — TGR 1.15, `pm_tgr_trade_center_trade_quantity_x5`"
project: vic3
audience: agent
source: tgr
aliases: ["Integrated Global Trade", "pm_tgr_trade_center_trade_quantity_x5"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_tgr_trade_center_trade_quantity_x5
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_trade.txt]
---
# Integrated Global Trade

Метод производства · `pm_tgr_trade_center_trade_quantity_x5` · `common/production_methods/TGR_TRADE_private_infrastructure_trade.txt:150`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/trade_quantity_4.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Бетонные верфи|Бетонные верфи]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-merchant-marine-add|goods_input_merchant_marine_add]] = `5` → [[tgr/Товары/Торговые корабли|Торговые корабли]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-trade-quantity-mult|state_trade_quantity_mult]] = `10.0`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-add|state_trade_capacity_add]] = `-20`
- **ai_value**: `200000`

## Ссылаются

- **Группы методов** (методы группы): [[tgr/Группы методов/Объём торговли (группа методов производства)|Объём торговли (группа методов производства)]]
