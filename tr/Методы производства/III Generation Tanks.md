---
type: concept
description: "Метод производства «III Generation Tanks» — T&R 1.13, `pm_third_gen_tank_production`"
project: vic3
source: tr
aliases: ["III Generation Tanks", "pm_third_gen_tank_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_third_gen_tank_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_military_production_methods.txt]
---
# III Generation Tanks

Метод производства · `pm_third_gen_tank_production` · `common/production_methods/ztr_military_production_methods.txt:177`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/third_gen_tanks.dds`
- **unlocking_technologies**: [[tr/Технологии/Main Battle Tank|Main Battle Tank]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_artillery_add` = `10` → [[vanilla/Товары/Артиллерия|Артиллерия]]
    - `goods_input_steel_add` = `26` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_alloys_add` = `12` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_output_automobiles_add` = `-15` → [[tr/Товары/Автомобили|Автомобили]]
    - `goods_output_tanks_add` = `70` → [[vanilla/Товары/Танки|Танки]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Танки|Танки]]
