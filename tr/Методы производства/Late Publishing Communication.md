---
type: concept
description: "Метод производства «Late Publishing Communication» — T&R 1.13, `manzoni_pm_telephone`"
project: vic3
source: tr
aliases: ["Late Publishing Communication", "manzoni_pm_telephone"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_telephone
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Late Publishing Communication

Метод производства · `manzoni_pm_telephone` · `common/production_methods/ztr_modified_mr_production_methods.txt:843`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_transmission_telephone.dds`
- **unlocking_technologies**: [[tr/Технологии/Телефон|Телефон]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_telephones_add` = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_electricity_add` = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_telecommunications_add` = `3` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_organized_data_add` = `4` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - `building_employment_academics_add` = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_laborers_add` = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `750` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Type of Communication|Type of Communication]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Circular Pressure Printing Machine|Circular Pressure Printing Machine]], [[tr/Методы производства/Digital Printers|Digital Printers]], [[tr/Методы производства/Linotype|Linotype]], [[tr/Методы производства/No Broadcast Media Industry|No Broadcast Media Industry]], [[tr/Методы производства/No Digital Media Industry|No Digital Media Industry]], [[tr/Методы производства/Offset Printing|Offset Printing]], [[tr/Методы производства/Printing Presses|Printing Presses]], [[tr/Методы производства/Rotary Press|Rotary Press]]
