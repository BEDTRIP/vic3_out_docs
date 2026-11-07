---
type: concept
description: "Метод производства «Steam Donkey» — E&F 1.13, `pm_steam_donkey_building_silver_mine`"
project: vic3
source: ef
aliases: ["Steam Donkey", "pm_steam_donkey_building_silver_mine"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_donkey_building_silver_mine
paths: [E&F/common/production_methods/03_ef_mines.txt]
---
# Steam Donkey

Метод производства · `pm_steam_donkey_building_silver_mine` · `common/production_methods/03_ef_mines.txt:244`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_donkey.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Паровик|Паровик]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `1` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silver-add|goods_output_silver_add]] = `-3` → [[ef/Товары/Silver|Silver]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Паровая автоматизация|Паровая автоматизация]]
