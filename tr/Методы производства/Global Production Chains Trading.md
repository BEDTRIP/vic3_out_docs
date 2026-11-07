---
type: concept
description: "Метод производства «Global Production Chains Trading» — T&R 1.13, `pm_trade_center_trade_quantity_ultra`"
project: vic3
source: tr
aliases: ["Global Production Chains Trading", "pm_trade_center_trade_quantity_ultra"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_trade_center_trade_quantity_ultra
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Global Production Chains Trading

Метод производства · `pm_trade_center_trade_quantity_ultra` · `common/production_methods/ztr_new_production_methods.txt:10447`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/trade_quantity_5.dds`
- **unlocking_technologies**: [[tr/Технологии/Naval Logistic Automation|Naval Logistic Automation]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_merchant_marine_add` = `8` → [[vanilla/Товары/Торговые корабли|Торговые корабли]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `-200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **unscaled**:
    - `state_trade_quantity_mult` = `1.5`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Объём торговли (группа методов производства)|Объём торговли (группа методов производства)]]
