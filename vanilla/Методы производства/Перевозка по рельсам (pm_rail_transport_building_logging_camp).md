---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_building_logging_camp)» — ваниль 1.13, `pm_rail_transport_building_logging_camp`"
project: vic3
source: vanilla
aliases: ["Перевозка по рельсам (pm_rail_transport_building_logging_camp)", "Перевозка по рельсам", "pm_rail_transport_building_logging_camp"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_building_logging_camp
paths: [.vanillaVIC3/common/production_methods/09_misc_resource.txt]
---
# Перевозка по рельсам (pm_rail_transport_building_logging_camp)

Метод производства · `pm_rail_transport_building_logging_camp` · `common/production_methods/09_misc_resource.txt:153`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Перевозка (pmg_transportation_building_logging_camp)|Перевозка (pmg_transportation_building_logging_camp)]]
