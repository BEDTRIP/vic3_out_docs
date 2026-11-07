---
type: concept
description: "Метод производства «Стандартное производство (pm_default_building_estacion_de_madrid_atocha)» — ваниль 1.13, `pm_default_building_estacion_de_madrid_atocha`"
project: vic3
source: vanilla
aliases: ["Стандартное производство (pm_default_building_estacion_de_madrid_atocha)", "Default Production", "pm_default_building_estacion_de_madrid_atocha"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_default_building_estacion_de_madrid_atocha
paths: [.vanillaVIC3/common/production_methods/08_monuments.txt]
---
# Стандартное производство (pm_default_building_estacion_de_madrid_atocha)

Метод производства · `pm_default_building_estacion_de_madrid_atocha` · `common/production_methods/08_monuments.txt:684`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **is_hidden_when_unavailable**: `yes`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `50`
    - `building_railway_throughput_add` = `0.20` → [[vanilla/Здания/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `200` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Основа (pmg_base_building_estacion_de_madrid_atocha)|Основа (pmg_base_building_estacion_de_madrid_atocha)]]
