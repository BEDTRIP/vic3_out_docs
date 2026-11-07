---
type: concept
description: "Метод производства «Morphine Extraction» — T&R 1.13, `pm_morphine_extraction`"
project: vic3
audience: agent
source: tr
aliases: ["Morphine Extraction", "pm_morphine_extraction"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_morphine_extraction
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Morphine Extraction

Метод производства · `pm_morphine_extraction` · `common/production_methods/ztr_new_production_methods.txt:7204`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/morphine.dds`
- **unlocking_technologies**: [[tr/Технологии/Penicillin|Penicillin]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-opium-add|goods_input_opium_add]] = `5` → [[vanilla/Товары/Опиум|Опиум]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_output_pharmaceuticals_add` = `15` → [[tr/Товары/Фармацевтика|Фармацевтика]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Opioids|Opioids]]
