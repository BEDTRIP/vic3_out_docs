---
type: concept
description: "Метод производства «Digital Communication» — T&R 1.13, `manzoni_pm_digital_media`"
project: vic3
source: tr
aliases: ["Digital Communication", "manzoni_pm_digital_media"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_digital_media
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Digital Communication

Метод производства · `manzoni_pm_digital_media` · `common/production_methods/ztr_new_production_methods.txt:9602`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_pm_digital_media.dds`
- **unlocking_technologies**: [[tr/Технологии/Global Music|Global Music]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_computer_add` = `5` → [[tr/Товары/Computers|Computers]]
    - `goods_input_televisions_add` = `5` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_telephones_add` = `10` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_telecommunications_add` = `15` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_organized_data_add` = `8` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `1000` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_academics_add` = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Type of Communication|Type of Communication]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Digital Audio Workstation|Digital Audio Workstation]], [[tr/Методы производства/Digital Postproduction|Digital Postproduction]], [[tr/Методы производства/No Broadcast Media Industry|No Broadcast Media Industry]], [[tr/Методы производства/No Publishing Industry|No Publishing Industry]], [[tr/Методы производства/Online Content Creation|Online Content Creation]]
