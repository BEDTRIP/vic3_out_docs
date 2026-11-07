---
type: concept
description: "Метод производства «Traditional Cosmetics» — T&R 1.13, `pm_traditional_perfumes_cosmetics`"
project: vic3
source: tr
aliases: ["Traditional Cosmetics", "pm_traditional_perfumes_cosmetics"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_traditional_perfumes_cosmetics
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Traditional Cosmetics

Метод производства · `pm_traditional_perfumes_cosmetics` · `common/production_methods/ztr_new_production_methods.txt:8945`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_traditional_perfumes_cosmetics.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Дистилляция|Дистилляция]]
- **state_modifiers**:
  - **unscaled**:
    - `state_mortality_mult` = `0.01`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_dye_add` = `30` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_fruit_add` = `10` → [[vanilla/Товары/Фрукты|Фрукты]]
    - `goods_input_glass_add` = `10` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_lead_add` = `5` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_input_liquor_add` = `15` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_output_cosmetics_add` = `60` → [[tr/Товары/Cosmetics|Cosmetics]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Cosmetics|Cosmetics]]
