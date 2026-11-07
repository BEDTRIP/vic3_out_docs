---
type: concept
description: "Метод производства «Mail» — T&R 1.13, `pm_air_mail`"
project: vic3
source: tr
aliases: ["Mail", "pm_air_mail"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_air_mail
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Mail

Метод производства · `pm_air_mail` · `common/production_methods/ztr_modified_mr_production_methods.txt:628`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_mail.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `10` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `18` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `100` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `150` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-government-administration-throughput-add|building_government_administration_throughput_add]] = `0.05` → [[vanilla/Здания/Правительственные ведомства|Правительственные ведомства]]
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Cargo Type|Cargo Type]]
