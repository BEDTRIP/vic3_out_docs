---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_gran_teatro_de_la_habana)» — ваниль 1.15, `pm_default_building_gran_teatro_de_la_habana`"
project: vic3
audience: agent
source: vanilla
aliases: ["Стандартное производство (pm_default_building_gran_teatro_de_la_habana)", "Default Production", "pm_default_building_gran_teatro_de_la_habana"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_gran_teatro_de_la_habana
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_gran_teatro_de_la_habana)

Метод производства · `pm_default_building_gran_teatro_de_la_habana` · `common/production_methods/08_monuments.txt:661`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `10` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fine-art-add|goods_output_fine_art_add]] = `5` → [[vanilla/Товары/Картины|Картины]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `200` → [[vanilla/Население/Типы/Учёные|Учёные]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_gran_teatro_de_la_habana)|Основа (pmg_base_building_gran_teatro_de_la_habana)]]
