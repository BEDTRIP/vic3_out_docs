---
type: concept
description: "Метод производства «Престиж (pm_monument_prestige_only_vatican_city)» — ваниль 1.15, `pm_monument_prestige_only_vatican_city`"
project: vic3
audience: agent
source: vanilla
aliases: ["Престиж (pm_monument_prestige_only_vatican_city)", "Престиж", "pm_monument_prestige_only_vatican_city"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_monument_prestige_only_vatican_city
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Престиж (pm_monument_prestige_only_vatican_city)

Метод производства · `pm_monument_prestige_only_vatican_city` · `common/production_methods/08_monuments.txt:259`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **disallowing_religions**: `catholic`
- **country_modifiers**:
  - **throughput_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основание (pmg_base_building_vatican_city)|Основание (pmg_base_building_vatican_city)]]
