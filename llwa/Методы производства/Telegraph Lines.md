---
type: concept
description: "Метод производства «Telegraph Lines» — LLWA 1.13, `LLWA_pm_telegraphs`"
project: vic3
source: llwa
aliases: ["Telegraph Lines", "LLWA_pm_telegraphs"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_telegraphs
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Telegraph Lines

Метод производства · `LLWA_pm_telegraphs` · `common/production_methods/LLWA_MAPI_bldgs.txt:216`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_telegraphs.dds`
- **ai_value**: `2000`
- **unlocking_technologies**: [[vanilla/Технологии/Электрический телеграф|Электрический телеграф]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-services-add|goods_input_services_add]] = `10` → [[vanilla/Товары/Услуги|Услуги]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-iron-add|goods_input_iron_add]] = `5` → [[vanilla/Товары/Железо|Железо]]
    - `goods_output_llwa_market_conn_add` = `20` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `50` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `50` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `50` → [[vanilla/Население/Типы/Механики|Механики]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.01`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.0005`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Information Distribution|Information Distribution]]
