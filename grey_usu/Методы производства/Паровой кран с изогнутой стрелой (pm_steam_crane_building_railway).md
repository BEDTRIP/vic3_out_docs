---
type: concept
description: "Метод производства «Паровой кран с изогнутой стрелой (pm_steam_crane_building_railway)» — grey USU 1.13, `pm_steam_crane_building_railway`"
project: vic3
audience: agent
source: grey_usu
aliases: ["Паровой кран с изогнутой стрелой (pm_steam_crane_building_railway)", "Curved Jib Steam Crane", "pm_steam_crane_building_railway"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_crane_building_railway
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_rail_other_pms.txt]
---
# Паровой кран с изогнутой стрелой (pm_steam_crane_building_railway)

Метод производства · `pm_steam_crane_building_railway` · `common/production_methods/yMoG_USU_rail_other_pms.txt:101`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_crane.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `2`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `1` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `1` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-600` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Автоматизация предприятия|Автоматизация предприятия]]
