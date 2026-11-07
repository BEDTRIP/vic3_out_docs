---
type: concept
description: "Метод производства «Паровые молотилки (pm_steam_threshers)» — ваниль 1.13, `pm_steam_threshers`"
project: vic3
source: vanilla
aliases: ["Паровые молотилки (pm_steam_threshers)", "Steam-Powered Thresher Machines", "pm_steam_threshers"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_threshers
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Паровые молотилки (pm_steam_threshers)

Метод производства · `pm_steam_threshers` · `common/production_methods/02_agro.txt:186`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steam_powered_threshers.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Молотильные машины|Молотильные машины]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `1` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Процесс сбора урожая (pmg_harvesting_process_building_maize_farm)|Процесс сбора урожая (pmg_harvesting_process_building_maize_farm)]], [[vanilla/Группы методов/Процесс сбора урожая (pmg_harvesting_process_building_millet_farm)|Процесс сбора урожая (pmg_harvesting_process_building_millet_farm)]], [[vanilla/Группы методов/Процесс сбора урожая (pmg_harvesting_process_building_rye_farm)|Процесс сбора урожая (pmg_harvesting_process_building_rye_farm)]], [[vanilla/Группы методов/Процесс сбора урожая (pmg_harvesting_process_building_wheat_farm)|Процесс сбора урожая (pmg_harvesting_process_building_wheat_farm)]]
