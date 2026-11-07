---
type: concept
description: "Метод производства «National Currency Production» — E&F 1.13, `pm_currency_liquidity_currency`"
project: vic3
source: ef
aliases: ["National Currency Production", "pm_currency_liquidity_currency"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_currency_liquidity_currency
paths: [E&F/common/production_methods/15_ef_bank.txt]
---
# National Currency Production

Метод производства · `pm_currency_liquidity_currency` · `common/production_methods/15_ef_bank.txt:264`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/currency_type.dds`
- **is_hidden_when_unavailable**: `yes`
- **disallowing_laws**: [[ef/Законы/No Market Liquidity|No Market Liquidity]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-liquidity-currency-add|goods_output_liquidity_currency_add]] = `1` → [[ef/Товары/Base Money|Base Money]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Currency Issued|Currency Issued]]
