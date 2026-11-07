---
type: concept
description: "Метод производства «Rudimental Chemical Pharmaceuticals» — T&R 1.13, `pm_rudimental_chemical_pharmaceuticals`"
project: vic3
source: tr
aliases: ["Rudimental Chemical Pharmaceuticals", "pm_rudimental_chemical_pharmaceuticals"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rudimental_chemical_pharmaceuticals
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Rudimental Chemical Pharmaceuticals

Метод производства · `pm_rudimental_chemical_pharmaceuticals` · `common/production_methods/ztr_new_production_methods.txt:7116`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_rudimental_chemical_pharmaceuticals.dds`
- **unlocking_technologies**: [[tr/Технологии/Microbiology|Microbiology]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_glass_add` = `15` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_input_liquor_add` = `20` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_output_pharmaceuticals_add` = `60` → [[tr/Товары/Фармацевтика|Фармацевтика]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Pharmaceuticals|Pharmaceuticals]]
