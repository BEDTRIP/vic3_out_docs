---
type: concept
description: "Метод производства «Инструменты для сбора урожая (pm_tools_building_rice_farm)» — TGR 1.13, `pm_tools_building_rice_farm`"
project: vic3
source: tgr
aliases: ["Инструменты для сбора урожая (pm_tools_building_rice_farm)", "Harvesting Tools", "pm_tools_building_rice_farm"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_tools_building_rice_farm
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Инструменты для сбора урожая (pm_tools_building_rice_farm)]]"
---
# Инструменты для сбора урожая (pm_tools_building_rice_farm)

Метод производства · `pm_tools_building_rice_farm` · `common/production_methods/TGR_TRADE_automation.txt:788`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/harvesting_tools.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `4` → [[tgr/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
