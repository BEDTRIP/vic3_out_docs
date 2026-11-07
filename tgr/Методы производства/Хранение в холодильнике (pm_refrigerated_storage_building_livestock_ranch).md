---
type: concept
description: "Метод производства «Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)» — TGR 1.13, `pm_refrigerated_storage_building_livestock_ranch`"
project: vic3
source: tgr
aliases: ["Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)", "Railway Storage", "pm_refrigerated_storage_building_livestock_ranch"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_storage_building_livestock_ranch
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)]]"
---
# Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)

Метод производства · `pm_refrigerated_storage_building_livestock_ranch` · `common/production_methods/TGR_TRADE_automation.txt:866`

## Отличия от ваниль

- **texture**: `"gfx/interface/icons/production_method_icons/refrigerated_storage.dds"` → `"gfx/interface/icons/production_method_icons/rail_transport.dds"`
- **unlocking_technologies**: изменено
- **building_modifiers**: изменено
- **required_input_goods**: убрано

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `2` → [[tgr/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
