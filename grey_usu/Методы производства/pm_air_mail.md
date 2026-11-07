---
type: concept
description: "Метод производства «pm_air_mail» — grey USU 1.13, `pm_air_mail`"
project: vic3
source: grey_usu
aliases: ["pm_air_mail"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_air_mail
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt]
---
# pm_air_mail

Метод производства · `pm_air_mail` · `common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt:164`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_mail.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `4` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `20` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `100` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-government-administration-throughput-add|building_government_administration_throughput_add]] = `0.025` → [[grey_usu/Здания/Правительственные ведомства|Правительственные ведомства]]
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
