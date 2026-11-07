---
type: concept
description: "Метод производства «Streaming Services» — T&R 1.13, `streaming_services`"
project: vic3
source: tr
aliases: ["Streaming Services", "streaming_services"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: streaming_services
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Streaming Services

Метод производства · `streaming_services` · `common/production_methods/ztr_new_production_methods.txt:8222`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_streaming_services.dds`
- **unlocking_technologies**: [[tr/Технологии/Social Media|Social Media]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_televisions_add` = `5` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_manzoni_prints_add` = `10` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_groceries_add` = `5` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_furniture_add` = `5` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - `goods_output_elgar_music_add` = `35` → [[tr/Товары/Entertainment|Entertainment]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `75` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Entertainment Type|Entertainment Type]]
