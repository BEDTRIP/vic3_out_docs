---
type: concept
description: "Метод производства «Паровик (pm_steam_donkey_building_coal_mine)» — TGR 1.13, `pm_steam_donkey_building_coal_mine`"
project: vic3
audience: agent
source: tgr
aliases: ["Паровик (pm_steam_donkey_building_coal_mine)", "Steam Donkey", "pm_steam_donkey_building_coal_mine"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_donkey_building_coal_mine
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Паровик (pm_steam_donkey_building_coal_mine)]]"
---
# Паровик (pm_steam_donkey_building_coal_mine)

Метод производства · `pm_steam_donkey_building_coal_mine` · `common/production_methods/TGR_TRADE_automation.txt:3`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_donkey.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Паровик|Паровик]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[tgr/Товары/Двигатели|Двигатели]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
