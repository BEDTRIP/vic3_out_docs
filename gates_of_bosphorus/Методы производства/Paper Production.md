---
type: concept
description: "Метод производства «Paper Production» — Gates of Bosphorus 1.15, `gbbf_esparto_papermill`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `15` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `10` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-paper-add|goods_output_paper_add]] = `40` → [[vanilla/Товары/Бумага|Бумага]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `500` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Primary Production|Primary Production]]
