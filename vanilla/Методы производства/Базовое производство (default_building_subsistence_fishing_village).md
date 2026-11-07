---
type: concept
description: "Метод производства «Базовое производство (default_building_subsistence_fishing_village)» — ваниль 1.13, `default_building_subsistence_fishing_village`"
project: vic3
source: vanilla
aliases: ["Базовое производство (default_building_subsistence_fishing_village)", "Базовое производство", "default_building_subsistence_fishing_village"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_subsistence_fishing_village
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Базовое производство (default_building_subsistence_fishing_village)

Метод производства · `default_building_subsistence_fishing_village` · `common/production_methods/12_subsistence.txt:275`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/subsistence_farming.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `0.5` → [[vanilla/Товары/Зерно|Зерно]]
    - `goods_output_fish_add` = `1.0` → [[vanilla/Товары/Рыба|Рыба]]
    - `goods_output_fabric_add` = `0.25` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_output_wood_add` = `0.25` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_output_services_add` = `0.5` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_peasants_add` = `5000` → [[vanilla/Население/Типы/Крестьяне|Крестьяне]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_subsistence_fishing_village)|Основа (pmg_base_building_subsistence_fishing_village)]]
