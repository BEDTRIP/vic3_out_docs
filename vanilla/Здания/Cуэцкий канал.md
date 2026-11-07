---
type: concept
description: "Здание «Cуэцкий канал» — ваниль 1.13, `building_suez_canal`"
project: vic3
source: vanilla
aliases: ["Cуэцкий канал", "Suez Canal", "building_suez_canal"]
tags: [ваниль, здание]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: building_suez_canal
paths: [.vanillaVIC3/common/buildings/10_canals.txt]
---
# Cуэцкий канал

Здание · `building_suez_canal` · `common/buildings/10_canals.txt:1`

## Поля

- **building_group**: [[vanilla/Группы зданий/Каналы|Каналы]]
- **icon**: `gfx/interface/icons/building_icons/suez_canal.dds`
- **strait**: `canal_suez`
- **expandable**: `no`
- **downsizeable**: `no`
- **unique**: `yes`
- **required_construction**: `construction_cost_canal`
- **ai_value**: `100000`
- **unlocking_technologies**: [[vanilla/Технологии/Колонизация|Колонизация]]
- **potential**: скрипт, строки 16–18
- **possible**: скрипт, строки 20–31
- **entity_not_constructed**: пусто
- **entity_under_construction**: `canal_suezcanal_under_construction_01_entity`
- **entity_constructed**: `canal_suezcanal_01_entity`
- **locator**: `canal_suez_locator`
- **city_gfx_interactions**:
  - `clear_collision_mesh_area` = `yes`
  - `clear_size_area` = `no`
- **production_method_groups**: [[vanilla/Группы методов/Канал (группа методов производства)|Канал (группа методов производства)]]
- **background**: `gfx/interface/icons/building_icons/backgrounds/building_panel_bg_harbour.dds`
