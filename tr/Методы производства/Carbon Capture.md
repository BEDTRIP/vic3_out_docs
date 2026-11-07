---
type: concept
description: "Метод производства «Carbon Capture» — T&R 1.13, `pm_urban_carbon_capture`"
project: vic3
source: tr
aliases: ["Carbon Capture", "pm_urban_carbon_capture"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_urban_carbon_capture
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Carbon Capture

Метод производства · `pm_urban_carbon_capture` · `common/production_methods/ztr_new_production_methods.txt:9316`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_carbon_capture.dds`
- **unlocking_technologies**: `carbon_capture_storage`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_water_add` = `0.5` → [[tr/Товары/Water|Water]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `-5`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.1`
- **disallowing_laws**: [[tr/Законы/No Enviroment Protection|No Enviroment Protection]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Carbon Capture (pmg_carbon_capture_building_urban_center)|Carbon Capture (pmg_carbon_capture_building_urban_center)]]
