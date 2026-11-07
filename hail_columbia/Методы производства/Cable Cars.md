---
type: concept
description: "Метод производства «Cable Cars» — Hail Columbia 1.13, `pm_usfp_brookyln_bridge_cable_cars`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Cable Cars", "pm_usfp_brookyln_bridge_cable_cars"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_usfp_brookyln_bridge_cable_cars
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Cable Cars

Метод производства · `pm_usfp_brookyln_bridge_cable_cars` · `common/production_methods/usfp_production_methods.txt:202`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/trains_electric.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.05` → [[vanilla/Здания/Городские центры|Городские центры]]

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Brooklyn Bridge|Brooklyn Bridge]]
