---
type: concept
description: "Метод производства «Удаленный доступ к торгам (usu_pm_port_c_logistics_2)» — grey USU 1.13, `usu_pm_port_c_logistics_2`"
project: vic3
source: grey_usu
aliases: ["Удаленный доступ к торгам (usu_pm_port_c_logistics_2)", "Remote Access Bidding", "usu_pm_port_c_logistics_2"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_port_c_logistics_2
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_port_other_pms.txt]
---
# Удаленный доступ к торгам (usu_pm_port_c_logistics_2)

Метод производства · `usu_pm_port_c_logistics_2` · `common/production_methods/yMoG_USU_port_other_pms.txt:35`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/log_2.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрический телеграф|Электрический телеграф]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_usu_logistics_add` = `7` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.1` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `-0.002` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.007` → [[grey_usu/Здания/Городские центры|Городские центры]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Логистика грузоперевозок|Логистика грузоперевозок]]
- **Методы производства** (unlocking_production_methods): [[grey_usu/Методы производства/Управление цепочками поставок (usu_pm_port_c_logistics_3)|Управление цепочками поставок (usu_pm_port_c_logistics_3)]]
