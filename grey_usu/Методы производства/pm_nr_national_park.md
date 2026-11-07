---
type: concept
description: "Метод производства «pm_nr_national_park» — grey USU 1.13, `pm_nr_national_park`"
project: vic3
source: grey_usu
aliases: ["pm_nr_national_park"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nr_national_park
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_dubois_pms.txt]
---
# pm_nr_national_park

Метод производства · `pm_nr_national_park` · `common/production_methods/mMoG_USU_MR_dubois_pms.txt:43`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dubois_nr_national_park_pm.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_paper_add` = `2` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_tools_add` = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_services_add` = `50` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `50` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_officers_add` = `50` → [[vanilla/Население/Типы/Офицеры|Офицеры]]
    - `building_employment_clerks_add` = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_academics_add` = `50` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **country_modifiers**:
  - **unscaled**:
    - `country_society_tech_research_speed_mult` = `0.01`
- **state_modifiers**:
  - **level_scaled**:
    - `state_pollution_generation_add` = `-100`
