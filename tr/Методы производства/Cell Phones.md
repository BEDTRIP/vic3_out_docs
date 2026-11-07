---
type: concept
description: "Метод производства «Cell Phones» — T&R 1.13, `pm_cell_phones`"
project: vic3
source: tr
aliases: ["Cell Phones", "pm_cell_phones"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cell_phones
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Cell Phones

Метод производства · `pm_cell_phones` · `common/production_methods/ztr_new_production_methods.txt:3959`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_cell_phone.dds`
- **unlocking_technologies**: [[tr/Технологии/Mobile Phone|Mobile Phone]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `10` → [[tr/Товары/Processors|Processors]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_telecommunications_add` = `25` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_telephones_add` = `125` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - `building_employment_academics_add` = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `2250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Телефоны|Телефоны]]
