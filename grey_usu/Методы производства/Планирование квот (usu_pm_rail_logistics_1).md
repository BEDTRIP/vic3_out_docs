---
type: concept
description: "Метод производства «Планирование квот (usu_pm_rail_logistics_1)» — grey USU 1.13, `usu_pm_rail_logistics_1`"
project: vic3
source: grey_usu
aliases: ["Планирование квот (usu_pm_rail_logistics_1)", "Quota Allowance Planning", "usu_pm_rail_logistics_1"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_rail_logistics_1
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_rail_station_pms.txt]
---
# Планирование квот (usu_pm_rail_logistics_1)

Метод производства · `usu_pm_rail_logistics_1` · `common/production_methods/yMoG_USU_rail_station_pms.txt:48`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/log_1.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Логистика|Логистика]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-merchant-marine-add|goods_input_merchant_marine_add]] = `1` → [[grey_usu/Товары/Торговые корабли|Торговые корабли]]
    - `goods_output_usu_logistics_add` = `42` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-port-throughput-add|building_port_throughput_add]] = `0.01` → [[grey_usu/Здания/Порты|Порты]]
    - `building_river_port_throughput_add` = `0.01` → [[grey_usu/Здания/Речные доки|Речные доки]]
  - **unscaled**:
    - `building_river_port_throughput_add` = `0.1` → [[grey_usu/Здания/Речные доки|Речные доки]]
- **ai_value**: `1000`

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Железнодорожная логистика|Железнодорожная логистика]]
