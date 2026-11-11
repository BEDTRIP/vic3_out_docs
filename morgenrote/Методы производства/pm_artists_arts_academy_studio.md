---
type: concept
description: "Метод производства «pm_artists_arts_academy_studio» — Morgenröte 1.15, `pm_artists_arts_academy_studio`"
project: vic3
audience: agent
source: morgenrote
aliases: ["pm_artists_arts_academy_studio"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_artists_arts_academy_studio
paths: [Morgenrote/common/production_methods/mr_arts_artists_production_methods.txt]
---
# pm_artists_arts_academy_studio

Метод производства · `pm_artists_arts_academy_studio` · `common/production_methods/mr_arts_artists_production_methods.txt:88`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_aa_art_studio_pm.dds`
- **unlocking_technologies**: [[morgenrote/Технологии/Реализм|Реализм]]
- **timed_modifiers**: `pm_artist_artistic_confusion_modifier`
- **country_modifiers**:
  - **unscaled**:
    - `country_artists_decorative_can_promote_painter_boolean` = `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `6` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-dye-add|goods_input_dye_add]] = `6` → [[vanilla/Товары/Красители|Красители]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-add|goods_output_fine_art_add]] = `3` → [[vanilla/Товары/Картины|Картины]]
- **ai_value**: `-1000`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Специализация Академии искусств|Специализация Академии искусств]]
