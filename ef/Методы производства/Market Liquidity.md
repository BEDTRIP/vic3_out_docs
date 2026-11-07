---
type: concept
description: "Метод производства «Market Liquidity» — E&F 1.13, `pm_market_liquidity_currency`"
project: vic3
audience: agent
source: ef
aliases: ["Market Liquidity", "pm_market_liquidity_currency"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_market_liquidity_currency
paths: [E&F/common/production_methods/00_ef_market_liquidity.txt]
---
# Market Liquidity

Метод производства · `pm_market_liquidity_currency` · `common/production_methods/00_ef_market_liquidity.txt:36`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/market_trade.dds`
- **disallowing_laws**: [[ef/Законы/No Market Liquidity|No Market Liquidity]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-liquidity-currency-add|goods_input_liquidity_currency_add]] = `98` → [[ef/Товары/Base Money|Base Money]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Market Liquidity|Market Liquidity]]
