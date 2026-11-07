---
type: concept
description: "Метод производства «Genetic Analysis» — T&R 1.13, `pm_genetic_analysis_breeding`"
project: vic3
audience: agent
source: tr
aliases: ["Genetic Analysis", "pm_genetic_analysis_breeding"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_genetic_analysis_breeding
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Genetic Analysis

Метод производства · `pm_genetic_analysis_breeding` · `common/production_methods/ztr_agriculture_production_methods.txt:217`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_genetic_analysis_breeding.dds`
- **unlocking_technologies**: [[tr/Технологии/Genetic Engineering|Genetic Engineering]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_pharmaceuticals_add` = `2` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - `goods_input_electroniccomponents_add` = `1` → [[tr/Товары/Electronic Components|Electronic Components]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.15`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Breeding|Breeding]]
