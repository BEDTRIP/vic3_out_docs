---
type: concept
description: "Метод производства «Automobiles» — Hail Columbia 1.13, `pm_usfp_brookyln_bridge_roadway`"
project: vic3
audience: agent
source: hail_columbia
aliases: ["Automobiles", "pm_usfp_brookyln_bridge_roadway"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_usfp_brookyln_bridge_roadway
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Automobiles

Метод производства · `pm_usfp_brookyln_bridge_roadway` · `common/production_methods/usfp_production_methods.txt:221`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/automobiles.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `10`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-automobiles-consumption-add|state_infrastructure_from_automobiles_consumption_add]] = `0.01`
    - [[vanilla/движок/Модификаторы B#^m-building-urban-center-throughput-add|building_urban_center_throughput_add]] = `0.10` → [[vanilla/Здания/Городские центры|Городские центры]]
- **unlocking_technologies**: [[vanilla/Технологии/Мощёные дороги|Мощёные дороги]]

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Brooklyn Bridge|Brooklyn Bridge]], [[hail_columbia/Группы методов/Golden Gate Bridge|Golden Gate Bridge]]
