---
type: concept
description: "Метод производства «Personal Computers» — T&R 1.13, `pm_personal_computers`"
project: vic3
source: tr
aliases: ["Personal Computers", "pm_personal_computers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_personal_computers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Personal Computers

Метод производства · `pm_personal_computers` · `common/production_methods/ztr_new_production_methods.txt:4562`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_personal_computers.dds`
- **unlocking_technologies**: [[tr/Технологии/Personal Computer|Personal Computer]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_batteries_add` = `5` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_softwares_add` = `10` → [[tr/Товары/Software|Software]]
    - `goods_input_televisions_add` = `10` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_processors_add` = `20` → [[tr/Товары/Processors|Processors]]
    - `goods_output_computer_add` = `60` → [[tr/Товары/Computers|Computers]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_engineers_add` = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_machinists_add` = `2250` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Computer|Computer]]
