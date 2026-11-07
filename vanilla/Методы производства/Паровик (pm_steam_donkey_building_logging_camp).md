---
type: concept
description: "Метод производства «Паровик (pm_steam_donkey_building_logging_camp)» — ваниль 1.13, `pm_steam_donkey_building_logging_camp`"
project: vic3
audience: agent
source: vanilla
aliases: ["Паровик (pm_steam_donkey_building_logging_camp)", "Steam Donkey", "pm_steam_donkey_building_logging_camp"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_donkey_building_logging_camp
paths: [.vanillaVIC3/common/production_methods/09_misc_resource.txt]
---
# Паровик (pm_steam_donkey_building_logging_camp)

Метод производства · `pm_steam_donkey_building_logging_camp` · `common/production_methods/09_misc_resource.txt:105`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_donkey.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Паровик|Паровик]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `1` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `4` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Специальное снаряжение|Специальное снаряжение]]
