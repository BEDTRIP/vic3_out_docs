---
type: concept
description: "Метод производства «pm_artists_arts_academy_salon» — Morgenröte 1.13, `pm_artists_arts_academy_salon`"
project: vic3
source: morgenrote
aliases: ["pm_artists_arts_academy_salon"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_artists_arts_academy_salon
paths: [Morgenrote/common/production_methods/mr_arts_artists_production_methods.txt]
---
# pm_artists_arts_academy_salon

Метод производства · `pm_artists_arts_academy_salon` · `common/production_methods/mr_arts_artists_production_methods.txt:60`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_aa_literary_salon_pm.dds`
- **unlocking_technologies**: пусто
- **timed_modifiers**: `pm_artist_artistic_confusion_modifier`
- **country_modifiers**:
  - **unscaled**:
    - `country_artists_decorative_can_promote_writer_boolean` = `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `6` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_manzoni_prints_add` = `4` → [[morgenrote/Товары/Газеты и книги|Газеты и книги]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-add|goods_output_fine_art_add]] = `3` → [[vanilla/Товары/Картины|Картины]]
- **ai_value**: `-1000`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Специализация Академии искусств|Специализация Академии искусств]]
