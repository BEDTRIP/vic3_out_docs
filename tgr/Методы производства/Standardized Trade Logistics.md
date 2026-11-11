---
type: concept
description: "Метод производства «Standardized Trade Logistics» — TGR 1.15, `pm_tgr_trade_center_trade_quantity_x4`"
project: vic3
audience: agent
source: tgr
aliases: ["Standardized Trade Logistics", "pm_tgr_trade_center_trade_quantity_x4"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_tgr_trade_center_trade_quantity_x4
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_private_infrastructure_trade.txt]
---
# Standardized Trade Logistics

Метод производства · `pm_tgr_trade_center_trade_quantity_x4` · `common/production_methods/TGR_TRADE_private_infrastructure_trade.txt:131`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/trade_quantity_4.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Плавучие волноломы|Плавучие волноломы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-merchant-marine-add|goods_input_merchant_marine_add]] = `4` → [[tgr/Товары/Торговые корабли|Торговые корабли]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-trade-quantity-mult|state_trade_quantity_mult]] = `7.5`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-trade-capacity-add|state_trade_capacity_add]] = `-15`
- **ai_value**: `150000`

## Ссылаются

- **Группы методов** (методы группы): [[tgr/Группы методов/Объём торговли (группа методов производства)|Объём торговли (группа методов производства)]]
