---
type: concept
description: "Метод производства «Commodities Listings» — LLWA 1.13, `LLWA_pm_commidities_listings`"
project: vic3
source: llwa
aliases: ["Commodities Listings", "LLWA_pm_commidities_listings"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_commidities_listings
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Commodities Listings

Метод производства · `LLWA_pm_commidities_listings` · `common/production_methods/LLWA_MAPI_bldgs.txt:99`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_commodities.dds`
- **ai_value**: `0`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_services_add` = `10` → [[vanilla/Товары/Услуги|Услуги]]
    - `goods_output_llwa_market_conn_add` = `10` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `800` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_market_access_price_impact` = `0.001`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_exchange_base)|Основа (LLWA_pmg_exchange_base)]]
