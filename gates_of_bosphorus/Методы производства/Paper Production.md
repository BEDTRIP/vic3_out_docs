---
type: concept
description: "Метод производства «Paper Production» — Gates of Bosphorus 1.13, `gbbf_esparto_papermill`"
project: vic3
source: gates_of_bosphorus
aliases: ["Paper Production", "gbbf_esparto_papermill"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_esparto_papermill
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_04_plantation_methods.txt]
---
# Paper Production

Метод производства · `gbbf_esparto_papermill` · `common/production_methods/gbbf_04_plantation_methods.txt:19`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pulp_pressing.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_wood_add` = `15` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_output_fabric_add` = `10` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_output_paper_add` = `40` → [[vanilla/Товары/Бумага|Бумага]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_farmers_add` = `500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Primary Production|Primary Production]]
