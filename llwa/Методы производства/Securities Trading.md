---
type: concept
description: "Метод производства «Securities Trading» — LLWA 1.13, `LLWA_pm_securities_trading`"
project: vic3
source: llwa
aliases: ["Securities Trading", "LLWA_pm_securities_trading"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_securities_trading
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Securities Trading

Метод производства · `LLWA_pm_securities_trading` · `common/production_methods/LLWA_MAPI_bldgs.txt:122`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_stocks.dds`
- **ai_value**: `1000`
- **unlocking_technologies**: [[vanilla/Технологии/Фондовая биржа|Фондовая биржа]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-services-add|goods_input_services_add]] = `25` → [[vanilla/Товары/Услуги|Услуги]]
    - `goods_output_llwa_market_conn_add` = `20` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `650` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `350` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.02`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.001`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_exchange_base)|Основа (LLWA_pmg_exchange_base)]]
