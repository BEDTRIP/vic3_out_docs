---
type: concept
description: "Метод производства «II Generation Tanks» — T&R 1.13, `pm_second_gen_tank_production`"
project: vic3
source: tr
aliases: ["II Generation Tanks", "pm_second_gen_tank_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_second_gen_tank_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# II Generation Tanks

Метод производства · `pm_second_gen_tank_production` · `common/production_methods/ztr_military_production_methods.txt:151`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/second_gen_tanks.dds`
- **unlocking_technologies**: [[tr/Технологии/Blitzkrieg|Blitzkrieg]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_artillery_add` = `10` → [[vanilla/Товары/Артиллерия|Артиллерия]]
    - `goods_input_steel_add` = `25` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_alloys_add` = `8` → [[tr/Товары/Alloys|Alloys]]
    - `goods_output_automobiles_add` = `-15` → [[tr/Товары/Автомобили|Автомобили]]
    - `goods_output_tanks_add` = `60` → [[vanilla/Товары/Танки|Танки]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `350` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Танки|Танки]]
