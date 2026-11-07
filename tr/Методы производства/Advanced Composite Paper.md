---
type: concept
description: "Метод производства «Advanced Composite Paper» — T&R 1.13, `pm_advanced_composite_paper`"
project: vic3
source: tr
aliases: ["Advanced Composite Paper", "pm_advanced_composite_paper"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_composite_paper
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Composite Paper

Метод производства · `pm_advanced_composite_paper` · `common/production_methods/ztr_new_production_methods.txt:8918`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_composite_paper.dds`
- **unlocking_technologies**: [[tr/Технологии/Laser|Laser]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_advancedores_add` = `10` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_dye_add` = `5` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_sulfur_add` = `15` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_paper_add` = `155` → [[vanilla/Товары/Бумага|Бумага]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_paper_mill)|Основа (pmg_base_building_paper_mill)]]
