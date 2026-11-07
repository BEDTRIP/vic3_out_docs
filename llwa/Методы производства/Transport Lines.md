---
type: concept
description: "Метод производства «Transport Lines» — LLWA 1.13, `LLWA_pm_transport_lines`"
project: vic3
audience: agent
source: llwa
aliases: ["Transport Lines", "LLWA_pm_transport_lines"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_transport_lines
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Transport Lines

Метод производства · `LLWA_pm_transport_lines` · `common/production_methods/LLWA_MAPI_bldgs.txt:38`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_shipping_lines.dds`
- **ai_value**: `1000`
- **unlocking_technologies**: [[vanilla/Технологии/Международная торговля|Международная торговля]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `30` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_llwa_market_conn_add` = `25` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.02`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.002`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_shipping_base)|Основа (LLWA_pmg_shipping_base)]]
