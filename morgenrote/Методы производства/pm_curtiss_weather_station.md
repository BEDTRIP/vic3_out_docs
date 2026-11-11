---
type: concept
description: "Метод производства «pm_curtiss_weather_station» — Morgenröte 1.15, `pm_curtiss_weather_station`"
project: vic3
audience: agent
source: morgenrote
aliases: ["pm_curtiss_weather_station"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_curtiss_weather_station
paths: [Morgenrote/common/production_methods/mr_sports_curtiss_production_methods.txt]
---
# pm_curtiss_weather_station

Метод производства · `pm_curtiss_weather_station` · `common/production_methods/mr_sports_curtiss_production_methods.txt:55`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/curtiss_weather_station_pm.dds`
- **unlocking_production_methods**: `pm_curtiss_weather_station`
- **unlocking_technologies**: [[morgenrote/Технологии/Разведывательный аэростат|Разведывательный аэростат]]
- **country_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-military-tech-research-speed-mult|country_military_tech_research_speed_mult]] = `0.03`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-drought-impact-mult|state_harvest_condition_drought_impact_mult]] = `-0.1`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-heatwave-impact-mult|state_harvest_condition_heatwave_impact_mult]] = `-0.1`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-flood-impact-mult|state_harvest_condition_flood_impact_mult]] = `-0.1`
    - `state_harvest_condition_torrential_rains_impact_mult` = `-0.1`
    - `state_harvest_condition_hailstorm_impact_mult` = `-0.1`
    - [[vanilla/движок/Модификаторы S#^m-state-harvest-condition-extreme-winds-impact-mult|state_harvest_condition_extreme_winds_impact_mult]] = `-0.1`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `10` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `10` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `100` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **ai_value**: `5000`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Метеорология|Метеорология]]
