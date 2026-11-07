---
type: concept
description: "Метод производства «Logistics Corporations» — LLWA 1.13, `LLWA_pm_logistics_company`"
project: vic3
source: llwa
aliases: ["Logistics Corporations", "LLWA_pm_logistics_company"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_logistics_company
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Logistics Corporations

Метод производства · `LLWA_pm_logistics_company` · `common/production_methods/LLWA_MAPI_bldgs.txt:68`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/financial_district.dds`
- **ai_value**: `2000`
- **unlocking_technologies**: [[vanilla/Технологии/Централизованное планирование|Централизованное планирование]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `50` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_llwa_market_conn_add` = `40` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `600` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `400` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **unscaled**:
    - `state_market_access_price_impact` = `0.04`
  - **workforce_scaled**:
    - `state_market_access_price_impact` = `0.003`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_shipping_base)|Основа (LLWA_pmg_shipping_base)]]
