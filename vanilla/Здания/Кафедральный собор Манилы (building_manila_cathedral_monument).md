---
type: concept
description: "Здание «Кафедральный собор Манилы (building_manila_cathedral_monument)» — ваниль 1.15, `building_manila_cathedral_monument`"
project: vic3
audience: agent
source: vanilla
aliases: ["Кафедральный собор Манилы (building_manila_cathedral_monument)", "Manila Cathedral", "building_manila_cathedral_monument"]
tags: [ваниль, здание]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: building_manila_cathedral_monument
paths: [.vanillaVIC3/common/buildings/08_monuments.txt]
---
# Кафедральный собор Манилы (building_manila_cathedral_monument)

Здание · `building_manila_cathedral_monument` · `common/buildings/08_monuments.txt:1441`

## Поля

- **building_group**: [[vanilla/Группы зданий/Монументы (bg_monuments)|Монументы (bg_monuments)]]
- **icon**: `gfx/interface/icons/building_icons/manila_cathedral.dds`
- **expandable**: `no`
- **buildable**: `yes`
- **downsizeable**: `no`
- **unique**: `yes`
- **locator**: `manila_cathedral`
- **entity_not_constructed**: пусто
- **entity_under_construction**: `building_construction_3x3_entity`
- **entity_constructed**: `wonder_manilacathedral_01_entity`
- **city_gfx_interactions**:
  - `clear_size_area` = `yes`
  - `size` = `4`
- **production_method_groups**: [[vanilla/Группы методов/Основа (pmg_base_building_manila_cathedral_monument)|Основа (pmg_base_building_manila_cathedral_monument)]]
- **required_construction**: `construction_cost_monument`
- **unlocking_technologies**: [[vanilla/Технологии/Железобетон|Железобетон]]
- **potential**: скрипт, строки 1469–1477
- **possible**: скрипт, строки 1479–1489
- **ai_value**: `10000`
- **background**: `gfx/interface/icons/building_icons/backgrounds/building_panel_bg_monuments.dds`
