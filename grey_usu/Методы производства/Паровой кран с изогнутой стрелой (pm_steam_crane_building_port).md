---
type: concept
description: "Метод производства «Паровой кран с изогнутой стрелой (pm_steam_crane_building_port)» — grey USU 1.13, `pm_steam_crane_building_port`"
project: vic3
source: grey_usu
aliases: ["Паровой кран с изогнутой стрелой (pm_steam_crane_building_port)", "Curved Jib Steam Crane", "pm_steam_crane_building_port"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_crane_building_port
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_port_other_pms.txt]
---
# Паровой кран с изогнутой стрелой (pm_steam_crane_building_port)

Метод производства · `pm_steam_crane_building_port` · `common/production_methods/yMoG_USU_port_other_pms.txt:166`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/port_crane.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **unlocking_production_methods**: [[grey_usu/Методы производства/Грузовой порт|Грузовой порт]], [[grey_usu/Методы производства/Риверсайд Пирс|Риверсайд Пирс]], [[grey_usu/Методы производства/Промышленный порт|Промышленный порт]], [[grey_usu/Методы производства/Промышленные порты|Промышленные порты]], [[grey_usu/Методы производства/Современный порт|Современный порт]], [[grey_usu/Методы производства/Современные порты|Современные порты]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `2`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `1` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `1` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Автоматизация объектов|Автоматизация объектов]]
