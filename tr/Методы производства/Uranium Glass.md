---
type: concept
description: "Метод производства «Uranium Glass» — T&R 1.13, `pm_curie_uranium_glass`"
project: vic3
source: tr
aliases: ["Uranium Glass", "pm_curie_uranium_glass"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_curie_uranium_glass
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Uranium Glass

Метод производства · `pm_curie_uranium_glass` · `common/production_methods/ztr_modified_mr_production_methods.txt:83`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/curie_uranium_glass.dds`
- **unlocking_technologies**: [[tr/Технологии/Nuclear Physics|Nuclear Physics]]
- **unlocking_production_methods**: [[vanilla/Методы производства/Хрустальное стекло|Хрустальное стекло]], [[tr/Методы производства/Пищевые пластики|Пищевые пластики]], [[tr/Методы производства/Houseware Inox-Aluminium|Houseware Inox-Aluminium]], [[tr/Методы производства/Houseware Moplen|Houseware Moplen]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_good_uranium_add` = `20` → [[tr/Товары/Uranium|Uranium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-dye-add|goods_input_dye_add]] = `5` → [[vanilla/Товары/Красители|Красители]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-glass-add|goods_output_glass_add]] = `-50` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-porcelain-add|goods_output_porcelain_add]] = `70` → [[vanilla/Товары/Фарфор|Фарфор]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство предметов роскоши (pmg_luxury_building_glassworks)|Производство предметов роскоши (pmg_luxury_building_glassworks)]]
