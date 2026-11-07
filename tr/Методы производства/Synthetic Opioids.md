---
type: concept
description: "Метод производства «Synthetic Opioids» — T&R 1.13, `pm_synthetic_opioids`"
project: vic3
source: tr
aliases: ["Synthetic Opioids", "pm_synthetic_opioids"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_synthetic_opioids
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Synthetic Opioids

Метод производства · `pm_synthetic_opioids` · `common/production_methods/ztr_new_production_methods.txt:7222`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/synthetic_opioids.dds`
- **unlocking_technologies**: [[tr/Технологии/Neuroscience|Neuroscience]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_opium_add` = `5` → [[vanilla/Товары/Опиум|Опиум]]
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_fertilizer_add` = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_output_pharmaceuticals_add` = `25` → [[tr/Товары/Фармацевтика|Фармацевтика]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Opioids|Opioids]]
