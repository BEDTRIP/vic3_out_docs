---
type: concept
description: "Метод производства «Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)» — ваниль 1.13, `pm_refrigerated_storage_building_livestock_ranch`"
project: vic3
source: vanilla
aliases: ["Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)", "Refrigerated Storage", "pm_refrigerated_storage_building_livestock_ranch"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_refrigerated_storage_building_livestock_ranch
paths: [.vanillaVIC3/common/production_methods/02_agro.txt]
---
# Хранение в холодильнике (pm_refrigerated_storage_building_livestock_ranch)

Метод производства · `pm_refrigerated_storage_building_livestock_ranch` · `common/production_methods/02_agro.txt:630`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/refrigerated_storage.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пастеризация|Пастеризация]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Охлаждение (pmg_refrigeration_building_livestock_ranch)|Охлаждение (pmg_refrigeration_building_livestock_ranch)]]
