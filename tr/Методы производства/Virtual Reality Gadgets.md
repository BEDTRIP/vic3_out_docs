---
type: concept
description: "Метод производства «Virtual Reality Gadgets» — T&R 1.13, `pm_virtual_reality_gadgets`"
project: vic3
source: tr
aliases: ["Virtual Reality Gadgets", "pm_virtual_reality_gadgets"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_virtual_reality_gadgets
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Virtual Reality Gadgets

Метод производства · `pm_virtual_reality_gadgets` · `common/production_methods/ztr_new_production_methods.txt:4013`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_virtual_reality_gadgets.dds`
- **unlocking_technologies**: [[tr/Технологии/Virtual Reality|Virtual Reality]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `15` → [[tr/Товары/Processors|Processors]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_softwares_add` = `8` → [[tr/Товары/Software|Software]]
    - `goods_input_ai_systems_add` = `8` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_telecommunications_add` = `35` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_telephones_add` = `165` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - `building_employment_academics_add` = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Телефоны|Телефоны]]
