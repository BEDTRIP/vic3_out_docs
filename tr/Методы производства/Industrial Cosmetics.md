---
type: concept
description: "Метод производства «Industrial Cosmetics» — T&R 1.13, `pm_industrial_cosmetics`"
project: vic3
source: tr
aliases: ["Industrial Cosmetics", "pm_industrial_cosmetics"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_industrial_cosmetics
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Industrial Cosmetics

Метод производства · `pm_industrial_cosmetics` · `common/production_methods/ztr_new_production_methods.txt:8977`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_industrial_cosmetics.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Автоматические воздуходувки|Автоматические воздуходувки]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_dye_add` = `30` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_fruit_add` = `20` → [[vanilla/Товары/Фрукты|Фрукты]]
    - `goods_input_glass_add` = `20` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_pharmaceuticals_add` = `15` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_output_cosmetics_add` = `80` → [[tr/Товары/Cosmetics|Cosmetics]]
    - `goods_output_fine_art_add` = `0.5` → [[vanilla/Товары/Картины|Картины]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Cosmetics|Cosmetics]]
