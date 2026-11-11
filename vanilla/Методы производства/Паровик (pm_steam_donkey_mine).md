---
type: concept
description: "Метод производства «Паровик (pm_steam_donkey_mine)» — ваниль 1.15, `pm_steam_donkey_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Паровик (pm_steam_donkey_mine)", "Steam Donkey", "pm_steam_donkey_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_donkey_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Паровик (pm_steam_donkey_mine)

Метод производства · `pm_steam_donkey_mine` · `common/production_methods/03_mines.txt:391`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_donkey.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Паровик|Паровик]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `1` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `4` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Паровая автоматизация (pmg_steam_automation_building_copper_mine)|Паровая автоматизация (pmg_steam_automation_building_copper_mine)]], [[vanilla/Группы методов/Паровая автоматизация (pmg_steam_automation_building_gold_mine)|Паровая автоматизация (pmg_steam_automation_building_gold_mine)]], [[vanilla/Группы методов/Паровая автоматизация (pmg_steam_automation_building_iron_mine)|Паровая автоматизация (pmg_steam_automation_building_iron_mine)]], [[vanilla/Группы методов/Паровая автоматизация (pmg_steam_automation_building_lead_mine)|Паровая автоматизация (pmg_steam_automation_building_lead_mine)]], [[vanilla/Группы методов/Паровая автоматизация (pmg_steam_automation_building_sulfur_mine)|Паровая автоматизация (pmg_steam_automation_building_sulfur_mine)]]
