---
type: concept
description: "Метод производства «GMO Crops (pm_ogm_building_rice_farm)» — T&R 1.13, `pm_ogm_building_rice_farm`"
project: vic3
source: tr
aliases: ["GMO Crops (pm_ogm_building_rice_farm)", "GMO Crops", "pm_ogm_building_rice_farm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_ogm_building_rice_farm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# GMO Crops (pm_ogm_building_rice_farm)

Метод производства · `pm_ogm_building_rice_farm` · `common/production_methods/ztr_agriculture_production_methods.txt:168`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_ogm.dds`
- **unlocking_technologies**: [[tr/Технологии/Genetic Engineering|Genetic Engineering]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `40` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_pharmaceuticals_add` = `5` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_output_grain_add` = `210` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `5000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `4000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_rice_farm)|Основа (pmg_base_building_rice_farm)]]
