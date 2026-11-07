---
type: concept
description: "Метод производства «Паровые молотилки (pm_steam_threshers)» — TGR 1.13, `pm_steam_threshers`"
project: vic3
source: tgr
aliases: ["Паровые молотилки (pm_steam_threshers)", "Steam-Powered Thresher Machines", "pm_steam_threshers"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_threshers
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Паровые молотилки (pm_steam_threshers)]]"
---
# Паровые молотилки (pm_steam_threshers)

Метод производства · `pm_steam_threshers` · `common/production_methods/TGR_TRADE_automation.txt:713`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_powered_threshers.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Молотильные машины|Молотильные машины]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `2` → [[tgr/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `1` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
