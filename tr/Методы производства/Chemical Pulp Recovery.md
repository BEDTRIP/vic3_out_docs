---
type: concept
description: "Метод производства «Chemical Pulp Recovery» — T&R 1.13, `pm_chemical_pulp_recovery`"
project: vic3
source: tr
aliases: ["Chemical Pulp Recovery", "pm_chemical_pulp_recovery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_chemical_pulp_recovery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Chemical Pulp Recovery

Метод производства · `pm_chemical_pulp_recovery` · `common/production_methods/ztr_new_production_methods.txt:8893`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_chemical_pulp_recovery.dds`
- **unlocking_technologies**: [[tr/Технологии/Kraft Recovery Process|Kraft Recovery Process]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_wood_add` = `20` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_dye_add` = `10` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_sulfur_add` = `10` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_paper_add` = `130` → [[vanilla/Товары/Бумага|Бумага]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_paper_mill)|Основа (pmg_base_building_paper_mill)]]
