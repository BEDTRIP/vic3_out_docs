---
type: concept
description: "Здание «Кайзерфорум (building_kaiserforum_1)» — ваниль 1.15, `building_kaiserforum_1`"
project: vic3
audience: agent
source: vanilla
aliases: ["Кайзерфорум (building_kaiserforum_1)", "Kaiserforum", "building_kaiserforum_1"]
tags: [ваниль, здание]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: building_kaiserforum_1
paths: [.vanillaVIC3/common/buildings/08_monuments.txt]
---
# Кайзерфорум (building_kaiserforum_1)

Здание · `building_kaiserforum_1` · `common/buildings/08_monuments.txt:899`

## Поля

- **building_group**: [[vanilla/Группы зданий/Монументы (bg_monuments)|Монументы (bg_monuments)]]
- **icon**: `gfx/interface/icons/building_icons/kaiserforum1.dds`
- **expandable**: `no`
- **downsizeable**: `no`
- **unique**: `yes`
- **locator**: `kaiserforum_locator`
- **entity_not_constructed**: пусто
- **entity_under_construction**: `building_construction_3x3_entity`
- **entity_constructed**: `wonder_the_kaiserforum_stage1_entity`
- **city_gfx_interactions**:
  - `clear_size_area` = `yes`
  - `size` = `4`
- **production_method_groups**: [[vanilla/Группы методов/Основа (pmg_base_building_kaiserforum_1)|Основа (pmg_base_building_kaiserforum_1)]]
- **required_construction**: `construction_cost_monument`
- **unlocking_technologies**: [[vanilla/Технологии/Железобетон|Железобетон]]
- **potential**: скрипт, строки 926–934
- **possible**: скрипт, строки 936–940
- **ai_value**: `10000`
- **background**: `gfx/interface/icons/building_icons/backgrounds/building_panel_bg_monuments.dds`
