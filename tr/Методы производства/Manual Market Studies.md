---
type: concept
description: "Метод производства «Manual Market Studies» — T&R 1.13, `pm_manual_market_studies`"
project: vic3
source: tr
aliases: ["Manual Market Studies", "pm_manual_market_studies"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manual_market_studies
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Manual Market Studies

Метод производства · `pm_manual_market_studies` · `common/production_methods/ztr_data_production_methods.txt:319`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_manual_market_studies.dds`
- **unlocking_technologies**: [[tr/Технологии/Market Studies|Market Studies]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `40` → [[tr/Товары/Organized Data|Organized Data]]
    - `goods_input_paper_add` = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_telephones_add` = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_electricity_add` = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_business_data_add` = `65` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `1000` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_academics_add` = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Section|Data Section]]
