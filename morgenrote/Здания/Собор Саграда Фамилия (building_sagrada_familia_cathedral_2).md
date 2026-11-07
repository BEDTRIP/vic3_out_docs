---
type: concept
description: "Здание «Собор Саграда Фамилия (building_sagrada_familia_cathedral_2)» — Morgenröte 1.13, `building_sagrada_familia_cathedral_2`"
project: vic3
source: morgenrote
aliases: ["Собор Саграда Фамилия (building_sagrada_familia_cathedral_2)", "Sagrada Família Cathedral", "building_sagrada_familia_cathedral_2"]
tags: [Morgenröte, здание]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: building_sagrada_familia_cathedral_2
paths: [Morgenrote/common/buildings/mr_vanilla_buildings_replace.txt]
replaces: "[[vanilla/Здания/Собор Саграда Фамилия (building_sagrada_familia_cathedral_2)]]"
---
# Собор Саграда Фамилия (building_sagrada_familia_cathedral_2)

Здание · `building_sagrada_familia_cathedral_2` · `common/buildings/mr_vanilla_buildings_replace.txt:164` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **production_method_groups**: изменено
- **potential**: изменено
- **possible**: изменено

## Поля

- **building_group**: [[vanilla/Группы зданий/Монументы (bg_monuments)|Монументы (bg_monuments)]]
- **icon**: `gfx/interface/icons/building_icons/sagrada_familia_cathedral2.dds`
- **expandable**: `no`
- **downsizeable**: `no`
- **unique**: `yes`
- **locator**: `sagrada_familia_cathedral`
- **entity_not_constructed**: ``
- **entity_under_construction**: `wonder_sagradafamilia_01_entity`
- **entity_constructed**: `wonder_sagradafamilia_02_entity`
- **city_gfx_interactions**:
  - `clear_size_area` = `yes`
  - `size` = `4`
- **production_method_groups**: [[morgenrote/Группы методов/Основа (pmg_base_building_sagrada_level_2)|Основа (pmg_base_building_sagrada_level_2)]]
- **required_construction**: `construction_cost_sagrada_familia`
- **potential**: скрипт, строки 189–196
- **possible**: скрипт, строки 198–202
- **ai_value**: `10000`
- **background**: `gfx/interface/icons/building_icons/backgrounds/building_panel_bg_monuments.dds`
