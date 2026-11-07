---
type: concept
description: "Метод производства «Continuous Cane Diffusion» — T&R 1.13, `pm_continuous_diffusion_sugar_cane_refining`"
project: vic3
source: tr
aliases: ["Continuous Cane Diffusion", "pm_continuous_diffusion_sugar_cane_refining"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_continuous_diffusion_sugar_cane_refining
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Continuous Cane Diffusion

Метод производства · `pm_continuous_diffusion_sugar_cane_refining` · `common/production_methods/ztr_agriculture_production_methods.txt:983`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_continuous_diffusion_sugar_refining.dds`
- **unlocking_technologies**: [[tr/Технологии/Controlled Environment Agriculture|Controlled Environment Agriculture]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - `goods_input_electricity_add` = `8` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_sugar_add` = `75` → [[vanilla/Товары/Сахар|Сахар]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Рафинирование|Рафинирование]]
