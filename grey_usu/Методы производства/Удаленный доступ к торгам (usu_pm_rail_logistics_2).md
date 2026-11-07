---
type: concept
description: "Метод производства «Удаленный доступ к торгам (usu_pm_rail_logistics_2)» — grey USU 1.13, `usu_pm_rail_logistics_2`"
project: vic3
source: grey_usu
aliases: ["Удаленный доступ к торгам (usu_pm_rail_logistics_2)", "Remote Access Bidding", "usu_pm_rail_logistics_2"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_rail_logistics_2
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_rail_station_pms.txt]
---
# Удаленный доступ к торгам (usu_pm_rail_logistics_2)

Метод производства · `usu_pm_rail_logistics_2` · `common/production_methods/yMoG_USU_rail_station_pms.txt:71`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/log_2.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрический телеграф|Электрический телеграф]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-merchant-marine-add|goods_input_merchant_marine_add]] = `2` → [[grey_usu/Товары/Торговые корабли|Торговые корабли]]
    - `goods_output_usu_logistics_add` = `84` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-port-throughput-add|building_port_throughput_add]] = `0.015` → [[grey_usu/Здания/Порты|Порты]]
    - `building_river_port_throughput_add` = `0.015` → [[grey_usu/Здания/Речные доки|Речные доки]]
  - **unscaled**:
    - `building_river_port_throughput_add` = `0.2` → [[grey_usu/Здания/Речные доки|Речные доки]]
- **ai_value**: `2000`

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Железнодорожная логистика|Железнодорожная логистика]]
- **Методы производства** (unlocking_production_methods): [[grey_usu/Методы производства/Управление цепочками поставок (usu_pm_rail_logistics_3)|Управление цепочками поставок (usu_pm_rail_logistics_3)]]
