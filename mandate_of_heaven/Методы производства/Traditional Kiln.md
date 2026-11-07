---
type: concept
description: "Метод производства «Traditional Kiln» — Mandate of Heaven 1.13, `pm_chinese_kiln`"
project: vic3
source: mandate_of_heaven
aliases: ["Traditional Kiln", "pm_chinese_kiln"]
tags: [mandate_of_heaven, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_chinese_kiln
paths: [for addon/Mandate of Heaven/common/production_methods/moh_production_methods.txt]
---
# Traditional Kiln

Метод производства · `pm_chinese_kiln` · `common/production_methods/moh_production_methods.txt:169`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/bone_china.dds`
- **unlocking_technologies**: [[mandate_of_heaven/Технологии/Chinese Kiln|Chinese Kiln]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_dye_add` = `6` → [[vanilla/Товары/Красители|Красители]]
    - `goods_output_glass_add` = `-15` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_output_porcelain_add` = `20` → [[vanilla/Товары/Фарфор|Фарфор]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[mandate_of_heaven/Группы методов/Производство предметов роскоши|Производство предметов роскоши]]
