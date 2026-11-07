---
type: concept
description: "Метод производства «Economic Journals» — LLWA 1.13, `LLWA_pm_econ_journals`"
project: vic3
audience: agent
source: llwa
aliases: ["Economic Journals", "LLWA_pm_econ_journals"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_econ_journals
paths: [llwa/common/production_methods/LLWA_MAPI_bldgs.txt]
---
# Economic Journals

Метод производства · `LLWA_pm_econ_journals` · `common/production_methods/LLWA_MAPI_bldgs.txt:188`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/newspapers.dds`
- **ai_value**: `1000`
- **unlocking_technologies**: [[vanilla/Технологии/Средства массовой информации|Средства массовой информации]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-services-add|goods_input_services_add]] = `5` → [[vanilla/Товары/Услуги|Услуги]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_output_llwa_market_conn_add` = `10` → [[llwa/Товары/Market Connectivity|Market Connectivity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `50` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.0005`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Information Distribution|Information Distribution]]
