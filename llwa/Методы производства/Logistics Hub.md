---
type: concept
description: "Метод производства «Logistics Hub» — LLWA 1.13, `LLWA_pm_logihub_base`"
project: vic3
source: llwa
aliases: ["Logistics Hub", "LLWA_pm_logihub_base"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_logihub_base
paths: [llwa/common/production_methods/LLWA_logihub.txt]
---
# Logistics Hub

Метод производства · `LLWA_pm_logihub_base` · `common/production_methods/LLWA_logihub.txt:6`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/trade_center.dds`
- **building_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `1` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_llwa_logi_conn_add` = `1` → [[llwa/Товары/Local Connectivity|Local Connectivity]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_logihub_base)|Основа (LLWA_pmg_logihub_base)]]
