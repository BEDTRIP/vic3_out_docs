---
type: concept
description: "Здание «Nuclear Weapons Silo» — T&R 1.13, `building_nuclear_weapons_silo`"
project: vic3
audience: agent
source: tr
aliases: ["Nuclear Weapons Silo", "building_nuclear_weapons_silo"]
tags: [tr, здание]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: building_nuclear_weapons_silo
paths: [TechRes+Kuromi/t&r/common/buildings/ztr_unique_buildings.txt]
---
# Nuclear Weapons Silo

Здание · `building_nuclear_weapons_silo` · `common/buildings/ztr_unique_buildings.txt:43`

## Поля

- **building_group**: [[tr/Группы зданий/bg_nuclear_weapons|bg_nuclear_weapons]]
- **icon**: `gfx/interface/icons/building_icons/nuclear_weapons_silo.dds`
- **buildable**: `yes`
- **expandable**: `no`
- **downsizeable**: `no`
- **levels_per_mesh**: `1`
- **unlocking_technologies**: [[tr/Технологии/Atomic Bomb|Atomic Bomb]]
- **production_method_groups**: [[tr/Группы методов/Nuclear Weapon Type|Nuclear Weapon Type]], [[tr/Группы методов/Stockpile Size|Stockpile Size]], [[tr/Группы методов/Nuclear Equipment Delivery Method|Nuclear Equipment Delivery Method]]
- **required_construction**: `construction_cost_modern`
- **possible**: скрипт, строки 60–74
- **background**: `gfx/interface/icons/building_icons/backgrounds/building_panel_bg_military.dds`
- **can_build_government**: скрипт, строки 76–81
- **can_build_private**: скрипт, строки 82–84
- **ai_value**: `50000`
