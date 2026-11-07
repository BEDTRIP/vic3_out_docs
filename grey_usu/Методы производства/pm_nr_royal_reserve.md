---
type: concept
description: "Метод производства «pm_nr_royal_reserve» — grey USU 1.13, `pm_nr_royal_reserve`"
project: vic3
audience: agent
source: grey_usu
aliases: ["pm_nr_royal_reserve"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nr_royal_reserve
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_dubois_pms.txt]
---
# pm_nr_royal_reserve

Метод производства · `pm_nr_royal_reserve` · `common/production_methods/mMoG_USU_MR_dubois_pms.txt:10`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dubois_nr_royal_reserve_pm.dds`
- **is_default**: `yes`
- **ai_value**: `500000`
- **disallowing_laws**: [[vanilla/Законы/Президентская республика|Президентская республика]], [[vanilla/Законы/Парламентская республика|Парламентская республика]], [[vanilla/Законы/Советская республика|Советская республика]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-small-arms-add|goods_input_small_arms_add]] = `2` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `20` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-soldiers-add|building_employment_soldiers_add]] = `100` → [[vanilla/Население/Типы/Военнослужащие|Военнослужащие]]
- **country_modifiers**: пусто
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-upper-strata-standard-of-living-add|state_upper_strata_standard_of_living_add]] = `0.2`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `-100`
