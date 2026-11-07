---
type: concept
description: "Метод производства «Паровые молотилки (pm_steam_threshers_building_rice_farm)» — TGR 1.13, `pm_steam_threshers_building_rice_farm`"
project: vic3
audience: agent
source: tgr
aliases: ["Паровые молотилки (pm_steam_threshers_building_rice_farm)", "Steam-Powered Thresher Machines", "pm_steam_threshers_building_rice_farm"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_threshers_building_rice_farm
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Паровые молотилки (pm_steam_threshers_building_rice_farm)]]"
---
# Паровые молотилки (pm_steam_threshers_building_rice_farm)

Метод производства · `pm_steam_threshers_building_rice_farm` · `common/production_methods/TGR_TRADE_automation.txt:803`

## Отличия от ваниль

- полей не меняет (тело как у ваниль)

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_powered_threshers.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Молотильные машины|Молотильные машины]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `4` → [[tgr/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `2` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
