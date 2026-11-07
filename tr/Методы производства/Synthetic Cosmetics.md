---
type: concept
description: "Метод производства «Synthetic Cosmetics» — T&R 1.13, `pm_synthetic_compounds_cosmetics`"
project: vic3
source: tr
aliases: ["Synthetic Cosmetics", "pm_synthetic_compounds_cosmetics"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_synthetic_compounds_cosmetics
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Synthetic Cosmetics

Метод производства · `pm_synthetic_compounds_cosmetics` · `common/production_methods/ztr_new_production_methods.txt:9003`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_synthetic_compounds_cosmetics.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Cosmetics|Synthetic Cosmetics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_dye_add` = `30` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_lubricant_add` = `10` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_fertilizer_add` = `10` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_glass_add` = `25` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_pharmaceuticals_add` = `25` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_output_cosmetics_add` = `105` → [[tr/Товары/Cosmetics|Cosmetics]]
    - `goods_output_fine_art_add` = `1` → [[vanilla/Товары/Картины|Картины]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Cosmetics|Cosmetics]]
