---
type: concept
description: "Метод производства «Clearing Houses» — LLWA 1.13, `LLWA_pm_clearing_houses`"
project: vic3
source: llwa
aliases: ["Clearing Houses", "LLWA_pm_clearing_houses"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_clearing_houses
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Clearing Houses

Метод производства · `LLWA_pm_clearing_houses` · `common/production_methods/LLWA_MAPI_bldgs.txt:152`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/stock_exchange.dds`
- **ai_value**: `2000`
- **unlocking_technologies**: [[vanilla/Технологии/Инвестиционные банки|Инвестиционные банки]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_services_add` = `40` → [[vanilla/Товары/Услуги|Услуги]]
    - `goods_output_llwa_market_conn_add` = `35` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **unscaled**:
    - `state_market_access_price_impact` = `0.05`
  - **workforce_scaled**:
    - `state_market_access_price_impact` = `0.002`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_exchange_base)|Основа (LLWA_pmg_exchange_base)]]
