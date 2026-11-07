---
type: concept
description: "Метод производства «Telephone Lines» — LLWA 1.13, `LLWA_pm_telephones`"
project: vic3
audience: agent
source: llwa
aliases: ["Telephone Lines", "LLWA_pm_telephones"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_telephones
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Telephone Lines

Метод производства · `LLWA_pm_telephones` · `common/production_methods/LLWA_MAPI_bldgs.txt:250`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_telephones.dds`
- **ai_value**: `3000`
- **unlocking_technologies**: [[vanilla/Технологии/Телефон|Телефон]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-services-add|goods_input_services_add]] = `15` → [[vanilla/Товары/Услуги|Услуги]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_llwa_market_conn_add` = `30` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `50` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `50` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `100` → [[vanilla/Население/Типы/Механики|Механики]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.02`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.001`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Information Distribution|Information Distribution]]
