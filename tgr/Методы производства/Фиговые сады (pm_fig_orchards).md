---
type: concept
description: "Метод производства «Фиговые сады (pm_fig_orchards)» — TGR 1.13, `pm_fig_orchards`"
project: vic3
source: tgr
aliases: ["Фиговые сады (pm_fig_orchards)", "Fig Orchards", "pm_fig_orchards"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fig_orchards
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_agro.txt]
replaces: "[[vanilla/Методы производства/Фиговые сады (pm_fig_orchards)]]"
---
# Фиговые сады (pm_fig_orchards)

Метод производства · `pm_fig_orchards` · `common/production_methods/TGR_TRADE_agro.txt:49`

## Отличия от ваниль

- **ai_value**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/orchards.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `-8` → [[tgr/Товары/Зерно|Зерно]]
    - `goods_output_fruit_add` = `7` → [[tgr/Товары/Фрукты|Фрукты]]
    - `goods_output_sugar_add` = `1` → [[tgr/Товары/Сахар|Сахар]]
- **ai_value**: `1`
