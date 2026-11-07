---
type: concept
description: "Метод производства «Планирование квот (usu_pm_port_r_logistics_1)» — grey USU 1.13, `usu_pm_port_r_logistics_1`"
project: vic3
source: grey_usu
aliases: ["Планирование квот (usu_pm_port_r_logistics_1)", "Quota Allowance Planning", "usu_pm_port_r_logistics_1"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_port_r_logistics_1
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_port_other_pms.txt]
---
# Планирование квот (usu_pm_port_r_logistics_1)

Метод производства · `usu_pm_port_r_logistics_1` · `common/production_methods/yMoG_USU_port_other_pms.txt:96`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/log_1.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Логистика|Логистика]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_usu_logistics_add` = `8` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
- **state_modifiers**:
  - **unscaled**:
    - `building_urban_center_throughput_add` = `0.1` → [[grey_usu/Здания/Городские центры|Городские центры]]
  - **workforce_scaled**:
    - `building_urban_center_throughput_add` = `0.02` → [[grey_usu/Здания/Городские центры|Городские центры]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Речная логистика|Речная логистика]]
