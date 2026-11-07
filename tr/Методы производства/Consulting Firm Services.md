---
type: concept
description: "Метод производства «Consulting Firm Services» — T&R 1.13, `pm_consulting_firm_services`"
project: vic3
source: tr
aliases: ["Consulting Firm Services", "pm_consulting_firm_services"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_consulting_firm_services
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Consulting Firm Services

Метод производства · `pm_consulting_firm_services` · `common/production_methods/ztr_data_production_methods.txt:397`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_consulting_firm_services_purple.dds`
- **unlocking_technologies**: [[tr/Технологии/Market Studies|Market Studies]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `40` → [[tr/Товары/Organized Data|Organized Data]]
    - `goods_input_paper_add` = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_telephones_add` = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_output_business_data_add` = `55` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `1250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_academics_add` = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Service Section|Service Section]]
