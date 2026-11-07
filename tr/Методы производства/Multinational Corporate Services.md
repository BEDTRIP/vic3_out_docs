---
type: concept
description: "Метод производства «Multinational Corporate Services» — T&R 1.13, `pm_multinational_corporate_services`"
project: vic3
audience: agent
source: tr
aliases: ["Multinational Corporate Services", "pm_multinational_corporate_services"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_multinational_corporate_services
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Multinational Corporate Services

Метод производства · `pm_multinational_corporate_services` · `common/production_methods/ztr_data_production_methods.txt:418`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_multinational_corporate_services_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Multinational Corporations|Multinational Corporations]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `55` → [[tr/Товары/Organized Data|Organized Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `8` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_output_business_data_add` = `75` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1000` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Service Section|Service Section]]
