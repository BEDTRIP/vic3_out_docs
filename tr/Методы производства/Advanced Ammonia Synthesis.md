---
type: concept
description: "Метод производства «Advanced Ammonia Synthesis» — T&R 1.13, `pm_advanced_ammonia_synthesis`"
project: vic3
source: tr
aliases: ["Advanced Ammonia Synthesis", "pm_advanced_ammonia_synthesis"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_ammonia_synthesis
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Ammonia Synthesis

Метод производства · `pm_advanced_ammonia_synthesis` · `common/production_methods/ztr_new_production_methods.txt:7674`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_ammonia_synthesis.dds`
- **unlocking_technologies**: [[tr/Технологии/Controlled Environment Agriculture|Controlled Environment Agriculture]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_sulfur_add` = `50` → [[vanilla/Товары/Сера|Сера]]
    - `goods_input_gas_add` = `25` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_advancedores_add` = `2` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_input_commonores_add` = `20` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_output_fertilizer_add` = `280` → [[vanilla/Товары/Удобрение|Удобрение]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство удобрений|Производство удобрений]]
