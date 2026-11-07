---
type: concept
description: "Метод производства «Инструменты для сбора урожая (pm_tools)» — TGR 1.13, `pm_tools`"
project: vic3
source: tgr
aliases: ["Инструменты для сбора урожая (pm_tools)", "Harvesting Tools", "pm_tools"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_tools
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Инструменты для сбора урожая (pm_tools)]]"
---
# Инструменты для сбора урожая (pm_tools)

Метод производства · `pm_tools` · `common/production_methods/TGR_TRADE_automation.txt:698`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/harvesting_tools.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `2` → [[tgr/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
