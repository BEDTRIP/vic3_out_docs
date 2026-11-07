---
type: concept
description: "Метод производства «Handcraft Natural Medicinals» — T&R 1.13, `pm_handcraft_natural_medicinals`"
project: vic3
source: tr
aliases: ["Handcraft Natural Medicinals", "pm_handcraft_natural_medicinals"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_handcraft_natural_medicinals
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Handcraft Natural Medicinals

Метод производства · `pm_handcraft_natural_medicinals` · `common/production_methods/ztr_new_production_methods.txt:7092`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/panum_clinic_pm_pharmaceuticals.dds`
- **unlocking_technologies**: [[tr/Технологии/Фармацевтика|Фармацевтика]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fruit_add` = `10` → [[vanilla/Товары/Фрукты|Фрукты]]
    - `goods_input_glass_add` = `10` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_input_liquor_add` = `20` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_output_pharmaceuticals_add` = `45` → [[tr/Товары/Фармацевтика|Фармацевтика]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Pharmaceuticals|Pharmaceuticals]]
