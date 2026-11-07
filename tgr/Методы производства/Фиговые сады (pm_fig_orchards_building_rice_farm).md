---
type: concept
description: "Метод производства «Фиговые сады (pm_fig_orchards_building_rice_farm)» — TGR 1.13, `pm_fig_orchards_building_rice_farm`"
project: vic3
source: tgr
aliases: ["Фиговые сады (pm_fig_orchards_building_rice_farm)", "Fig Orchards", "pm_fig_orchards_building_rice_farm"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fig_orchards_building_rice_farm
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_agro.txt]
replaces: "[[vanilla/Методы производства/Фиговые сады (pm_fig_orchards_building_rice_farm)]]"
---
# Фиговые сады (pm_fig_orchards_building_rice_farm)

Метод производства · `pm_fig_orchards_building_rice_farm` · `common/production_methods/TGR_TRADE_agro.txt:35`

## Отличия от ваниль

- **ai_value**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/orchards.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `-20` → [[tgr/Товары/Зерно|Зерно]]
    - `goods_output_fruit_add` = `15` → [[tgr/Товары/Фрукты|Фрукты]]
    - `goods_output_sugar_add` = `2` → [[tgr/Товары/Сахар|Сахар]]
- **ai_value**: `1`
