---
type: concept
description: "Метод производства «Wöhler-Deville Process» — T&R 1.13, `pm_wohler_deville_process`"
project: vic3
audience: agent
source: tr
aliases: ["Wöhler-Deville Process", "pm_wohler_deville_process"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_wohler_deville_process
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Wöhler-Deville Process

Метод производства · `pm_wohler_deville_process` · `common/production_methods/ztr_new_production_methods.txt:5732`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/blister_steel_process.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[tr/Технологии/Wöhler-Deville Process|Wöhler-Deville Process]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_bauxite_add` = `50` → [[tr/Товары/Bauxite|Bauxite]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `3` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-sulfur-add|goods_input_sulfur_add]] = `3` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_alloys_add` = `-10` → [[tr/Товары/Alloys|Alloys]]
    - `goods_output_aluminium_add` = `55` → [[tr/Товары/Aluminium|Aluminium]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Aluminium Process|Aluminium Process]]
