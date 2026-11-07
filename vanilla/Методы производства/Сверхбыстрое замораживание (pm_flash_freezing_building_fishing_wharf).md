---
type: concept
description: "Метод производства «Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)» — ваниль 1.13, `pm_flash_freezing_building_fishing_wharf`"
project: vic3
source: vanilla
aliases: ["Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)", "Flash Freezing", "pm_flash_freezing_building_fishing_wharf"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_flash_freezing_building_fishing_wharf
paths: [.vanillaVIC3/common/production_methods/09_misc_resource.txt]
---
# Сверхбыстрое замораживание (pm_flash_freezing_building_fishing_wharf)

Метод производства · `pm_flash_freezing_building_fishing_wharf` · `common/production_methods/09_misc_resource.txt:362`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/flash_refrigerated.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сверхбыстрое замораживание|Сверхбыстрое замораживание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `7` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_transportation_add` = `7` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Охлаждение (pmg_refrigeration_building_fishing_wharf)|Охлаждение (pmg_refrigeration_building_fishing_wharf)]]
