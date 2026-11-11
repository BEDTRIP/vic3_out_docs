---
type: concept
description: "Метод производства «Нитроглицерин (pm_nitroglycerin_building_coal_mine)» — ваниль 1.15, `pm_nitroglycerin_building_coal_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Нитроглицерин (pm_nitroglycerin_building_coal_mine)", "Nitroglycerin", "pm_nitroglycerin_building_coal_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nitroglycerin_building_coal_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Нитроглицерин (pm_nitroglycerin_building_coal_mine)

Метод производства · `pm_nitroglycerin_building_coal_mine` · `common/production_methods/03_mines.txt:118`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/nitroglycerin.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Нитроглицерин|Нитроглицерин]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `5` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coal-add|goods_output_coal_add]] = `15` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-laborers-mortality-mult|building_laborers_mortality_mult]] = `0.3`
    - [[vanilla/движок/Модификаторы B#^m-building-machinists-mortality-mult|building_machinists_mortality_mult]] = `0.2`
    - [[vanilla/движок/Модификаторы B#^m-building-engineers-mortality-mult|building_engineers_mortality_mult]] = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Взрывчатка (pmg_explosives_building_coal_mine)|Взрывчатка (pmg_explosives_building_coal_mine)]]
