---
type: concept
description: "Метод производства «Electronic News Gathering» — T&R 1.13, `pm_electronic_news_gathering`"
project: vic3
source: tr
aliases: ["Electronic News Gathering", "pm_electronic_news_gathering"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electronic_news_gathering
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electronic News Gathering

Метод производства · `pm_electronic_news_gathering` · `common/production_methods/ztr_new_production_methods.txt:9456`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electronic_news_gathering.dds`
- **unlocking_technologies**: [[tr/Технологии/Массовая агитация|Массовая агитация]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_paper_add` = `25` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_copperwires_add` = `20` → [[tr/Товары/Wires|Wires]]
    - `goods_output_manzoni_prints_add` = `75` → [[tr/Товары/Media Content|Media Content]]
    - `goods_output_elgar_music_add` = `20` → [[tr/Товары/Entertainment|Entertainment]]
- **unlocking_production_methods**: [[tr/Методы производства/Broadcasting Communication|Broadcasting Communication]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Broadcast Media Production|Broadcast Media Production]]
