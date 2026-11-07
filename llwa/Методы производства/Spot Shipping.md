---
type: concept
description: "Метод производства «Spot Shipping» — LLWA 1.13, `LLWA_pm_spot_shipping`"
project: vic3
source: llwa
aliases: ["Spot Shipping", "LLWA_pm_spot_shipping"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_spot_shipping
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Spot Shipping

Метод производства · `LLWA_pm_spot_shipping` · `common/production_methods/LLWA_MAPI_bldgs.txt:12`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_spot_shipping.dds`
- **ai_value**: `0`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_llwa_market_conn_add` = `10` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `900` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.01`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.001`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_shipping_base)|Основа (LLWA_pmg_shipping_base)]]
