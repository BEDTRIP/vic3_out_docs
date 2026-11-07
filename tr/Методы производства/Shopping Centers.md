---
type: concept
description: "Метод производства «Shopping Centers» — T&R 1.13, `pm_shopping_centers`"
project: vic3
source: tr
aliases: ["Shopping Centers", "pm_shopping_centers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_shopping_centers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Shopping Centers

Метод производства · `pm_shopping_centers` · `common/production_methods/ztr_new_production_methods.txt:6762`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_shopping_centers.dds`
- **unlocking_technologies**: [[tr/Технологии/Supermarket|Supermarket]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_glass_add` = `3` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_steel_add` = `1` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_alloys_add` = `1` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_electricity_add` = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_services_add` = `35` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `1750` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Блага|Блага]]
