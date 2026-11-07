---
type: concept
description: "Здание «Кайзерфорум (building_kaiserforum_3)» — ваниль 1.13, `building_kaiserforum_3`"
project: vic3
source: vanilla
aliases: ["Кайзерфорум (building_kaiserforum_3)", "Kaiserforum", "building_kaiserforum_3"]
tags: [ваниль, здание]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: building_kaiserforum_3
paths: [.vanillaVIC3/common/buildings/08_monuments.txt]
---
# Кайзерфорум (building_kaiserforum_3)

Здание · `building_kaiserforum_3` · `common/buildings/08_monuments.txt:992`

## Поля

- **building_group**: [[vanilla/Группы зданий/Монументы (bg_monuments)|Монументы (bg_monuments)]]
- **icon**: `gfx/interface/icons/building_icons/kaiserforum3.dds`
- **expandable**: `no`
- **downsizeable**: `no`
- **unique**: `yes`
- **locator**: `kaiserforum_locator`
- **entity_not_constructed**: пусто
- **entity_under_construction**: `wonder_the_kaiserforum_stage2_entity`
- **entity_constructed**: `wonder_the_kaiserforum_entity`
- **city_gfx_interactions**:
  - `clear_size_area` = `yes`
  - `size` = `4`
- **production_method_groups**: [[vanilla/Группы методов/Основа (pmg_base_building_kaiserforum_3)|Основа (pmg_base_building_kaiserforum_3)]]
- **required_construction**: `construction_cost_monument`
- **potential**: скрипт, строки 1015–1024
- **possible**: скрипт, строки 1026–1033
- **ai_value**: `10000`
- **background**: `gfx/interface/icons/building_icons/backgrounds/building_panel_bg_monuments.dds`
