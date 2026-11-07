---
type: concept
description: "Метод производства «Isoprene» — T&R 1.13, `pm_mendelejew_isoprene`"
project: vic3
audience: agent
source: tr
aliases: ["Isoprene", "pm_mendelejew_isoprene"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mendelejew_isoprene
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Isoprene

Метод производства · `pm_mendelejew_isoprene` · `common/production_methods/ztr_modified_mr_production_methods.txt:38`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mendelejew_isoprene_pm.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Rubber|Synthetic Rubber]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-sulfur-add|goods_input_sulfur_add]] = `7` → [[vanilla/Товары/Сера|Сера]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_light_fuel_add` = `15` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-rubber-add|goods_output_rubber_add]] = `55` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_output_plastics_add` = `-10` → [[tr/Товары/Пластмассы|Пластмассы]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Synthetic Rubber|Synthetic Rubber]]
