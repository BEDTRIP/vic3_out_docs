---
type: concept
description: "Метод производства «Управление цепочками поставок (usu_pm_port_c_logistics_3)» — grey USU 1.13, `usu_pm_port_c_logistics_3`"
project: vic3
source: grey_usu
aliases: ["Управление цепочками поставок (usu_pm_port_c_logistics_3)", "Supply Chain Management", "usu_pm_port_c_logistics_3"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_port_c_logistics_3
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_port_other_pms.txt]
---
# Управление цепочками поставок (usu_pm_port_c_logistics_3)

Метод производства · `usu_pm_port_c_logistics_3` · `common/production_methods/yMoG_USU_port_other_pms.txt:58`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/log_3.dds`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Удаленный доступ к торгам (usu_pm_port_c_logistics_2)|Удаленный доступ к торгам (usu_pm_port_c_logistics_2)]], `usu_pm_port_c_logistics_3`
- **unlocking_technologies**: [[vanilla/Технологии/Корпоративное управление|Корпоративное управление]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_usu_logistics_add` = `10.5` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.1` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `-0.003` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.01` → [[grey_usu/Здания/Городские центры|Городские центры]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Логистика грузоперевозок|Логистика грузоперевозок]]
