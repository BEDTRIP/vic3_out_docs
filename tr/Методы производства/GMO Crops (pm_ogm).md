---
type: concept
description: "Метод производства «GMO Crops (pm_ogm)» — T&R 1.13, `pm_ogm`"
project: vic3
source: tr
aliases: ["GMO Crops (pm_ogm)", "GMO Crops", "pm_ogm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_ogm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# GMO Crops (pm_ogm)

Метод производства · `pm_ogm` · `common/production_methods/ztr_agriculture_production_methods.txt:145`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_ogm.dds`
- **unlocking_technologies**: [[tr/Технологии/Genetic Engineering|Genetic Engineering]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `25` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_pharmaceuticals_add` = `5` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_output_grain_add` = `120` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `2000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_maize_farm)|Основа (pmg_base_building_maize_farm)]], [[tr/Группы методов/Основа (pmg_base_building_millet_farm)|Основа (pmg_base_building_millet_farm)]], [[tr/Группы методов/Основа (pmg_base_building_rye_farm)|Основа (pmg_base_building_rye_farm)]], [[tr/Группы методов/Основа (pmg_base_building_wheat_farm)|Основа (pmg_base_building_wheat_farm)]]
