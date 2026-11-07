---
type: concept
description: "Метод производства «Базовое производство (default_building_subsistence_pasture)» — ваниль 1.13, `default_building_subsistence_pasture`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_subsistence_pasture)", "Базовое производство", "default_building_subsistence_pasture"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_subsistence_pasture
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Базовое производство (default_building_subsistence_pasture)

Метод производства · `default_building_subsistence_pasture` · `common/production_methods/12_subsistence.txt:212`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/subsistence_farming.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `0.25` → [[vanilla/Товары/Зерно|Зерно]]
    - `goods_output_meat_add` = `0.5` → [[vanilla/Товары/Мясо|Мясо]]
    - `goods_output_fabric_add` = `0.75` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_output_wood_add` = `0.25` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_output_services_add` = `0.5` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_peasants_add` = `5000` → [[vanilla/Население/Типы/Крестьяне|Крестьяне]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_subsistence_pasture)|Основа (pmg_base_building_subsistence_pasture)]]
