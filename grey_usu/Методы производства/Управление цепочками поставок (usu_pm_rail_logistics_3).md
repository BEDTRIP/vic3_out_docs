---
type: concept
description: "Метод производства «Управление цепочками поставок (usu_pm_rail_logistics_3)» — grey USU 1.13, `usu_pm_rail_logistics_3`"
project: vic3
source: grey_usu
aliases: ["Управление цепочками поставок (usu_pm_rail_logistics_3)", "Supply Chain Management", "usu_pm_rail_logistics_3"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_rail_logistics_3
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_rail_station_pms.txt]
---
# Управление цепочками поставок (usu_pm_rail_logistics_3)

Метод производства · `usu_pm_rail_logistics_3` · `common/production_methods/yMoG_USU_rail_station_pms.txt:94`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/log_3.dds`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Удаленный доступ к торгам (usu_pm_rail_logistics_2)|Удаленный доступ к торгам (usu_pm_rail_logistics_2)]], `usu_pm_rail_logistics_3`
- **unlocking_technologies**: [[vanilla/Технологии/Корпоративное управление|Корпоративное управление]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_merchant_marine_add` = `3` → [[grey_usu/Товары/Торговые корабли|Торговые корабли]]
    - `goods_output_usu_logistics_add` = `126` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
- **state_modifiers**:
  - **level_scaled**:
    - `building_port_throughput_add` = `0.02` → [[grey_usu/Здания/Порты|Порты]]
    - `building_river_port_throughput_add` = `0.02` → [[grey_usu/Здания/Речные доки|Речные доки]]
  - **unscaled**:
    - `building_river_port_throughput_add` = `0.3` → [[grey_usu/Здания/Речные доки|Речные доки]]
- **ai_value**: `3000`

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Железнодорожная логистика|Железнодорожная логистика]]
