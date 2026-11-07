---
type: concept
description: "Метод производства «Hormonal Feedlots» — T&R 1.13, `pm_hormonal_feedlots`"
project: vic3
source: tr
aliases: ["Hormonal Feedlots", "pm_hormonal_feedlots"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hormonal_feedlots
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Hormonal Feedlots

Метод производства · `pm_hormonal_feedlots` · `common/production_methods/ztr_agriculture_production_methods.txt:197`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_hormonal_feedlots.dds`
- **unlocking_technologies**: [[tr/Технологии/Fast Food|Fast Food]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_pharmaceuticals_add` = `1` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_input_groceries_add` = `1` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_tools_add` = `1` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **unscaled**:
    - `building_throughput_add` = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Breeding|Breeding]]
