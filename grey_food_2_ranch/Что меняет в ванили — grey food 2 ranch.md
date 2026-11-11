---
type: reference
description: "Что мод grey food 2 ranch меняет в ванили 1.15 (снимок мода — 1.13): записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: grey_food_2_ranch
tags: [grey_food_2_ranch, что-меняет]
generated: "v3 graph mods"
paths: [grey_add_alot_of_things/grey_food_2_ranch/**]
---
# Что меняет в ванили — grey food 2 ranch

Снимок `grey_add_alot_of_things/grey_food_2_ranch` (снимок мода — 1.13), сравнение с ваниль 1.15. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `buildings` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `company_types` | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `pop_needs` | 0 | 1 | 1 | 0 | 0 | 0 | 0 |
| `production_method_groups` | 2 | 4 | 0 | 0 | 0 | 0 | 0 |
| `production_methods` | 11 | 12 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `technology/technologies` | 0 | 0 | 1 | 0 | 0 | 0 | 0 |

### buildings

- **заменяет** (1): [[grey_food_2_ranch/Здания/Животноводческие фермы|Животноводческие фермы]]

### company_types

- **добавляет** (1): [[grey_food_2_ranch/Виды компаний/Синдикат продовольственной сети Кардхо|Синдикат продовольственной сети Кардхо]]
- **заменяет** (1): [[grey_food_2_ranch/Виды компаний/Элитная еда|Элитная еда]]

### modifier_type_definitions

- **добавляет** (2): `goods_output_grain_mult`, `goods_output_meat_mult`

### pop_needs

- **заменяет** (1): [[grey_food_2_ranch/Население/Потребности/Дорогая еда|Дорогая еда]]
- **дополняет** (1): [[grey_food_2_ranch/Население/Потребности/Простая еда|Простая еда]]

### production_method_groups

- **добавляет** (2): [[grey_food_2_ranch/Группы методов/pmg_automation_ranch|pmg_automation_ranch]], [[grey_food_2_ranch/Группы методов/pmg_dairy_products|pmg_dairy_products]]
- **заменяет** (4): [[grey_food_2_ranch/Группы методов/Основа|Основа]], [[grey_food_2_ranch/Группы методов/Ограждение|Ограждение]], [[grey_food_2_ranch/Группы методов/Охлаждение|Охлаждение]], [[grey_food_2_ranch/Группы методов/Производство шерсти|Производство шерсти]]

### production_methods

- **добавляет** (11): [[grey_food_2_ranch/Методы производства/pm_artisanal_cheese|pm_artisanal_cheese]], [[grey_food_2_ranch/Методы производства/pm_battery_farming|pm_battery_farming]], [[grey_food_2_ranch/Методы производства/pm_beasts_of_burden|pm_beasts_of_burden]], [[grey_food_2_ranch/Методы производства/pm_full_eggs_dairy|pm_full_eggs_dairy]], [[grey_food_2_ranch/Методы производства/pm_homemade_tools|pm_homemade_tools]], [[grey_food_2_ranch/Методы производства/pm_industrial_preserves|pm_industrial_preserves]], [[grey_food_2_ranch/Методы производства/pm_intensive_diet_control|pm_intensive_diet_control]], [[grey_food_2_ranch/Методы производства/pm_no_cheese|pm_no_cheese]], [[grey_food_2_ranch/Методы производства/pm_ranch_milk_production|pm_ranch_milk_production]], [[grey_food_2_ranch/Методы производства/pm_refrigerated_workspaces|pm_refrigerated_workspaces]], [[grey_food_2_ranch/Методы производства/pm_unrefrigerated_ranch|pm_unrefrigerated_ranch]]
- **заменяет** (12): [[grey_food_2_ranch/Методы производства/Изгороди с колючей проволокой|Изгороди с колючей проволокой]], [[grey_food_2_ranch/Методы производства/Инструменты скотобойни|Инструменты скотобойни]], [[grey_food_2_ranch/Методы производства/Электрические изгороди|Электрические изгороди]], [[grey_food_2_ranch/Методы производства/Интенсивный сбор шерсти|Интенсивный сбор шерсти]], [[grey_food_2_ranch/Методы производства/Механизированные скотобойни|Механизированные скотобойни]], [[grey_food_2_ranch/Методы производства/Скотные дворы под открытым воздухом|Скотные дворы под открытым воздухом]], [[grey_food_2_ranch/Методы производства/Вагоны-рефрижераторы|Вагоны-рефрижераторы]], [[grey_food_2_ranch/Методы производства/Хранение в холодильнике|Хранение в холодильнике]], [[grey_food_2_ranch/Методы производства/Увеличенный сбор шерсти|Увеличенный сбор шерсти]], [[grey_food_2_ranch/Методы производства/Овцеводческие ранчо|Овцеводческие ранчо]], [[grey_food_2_ranch/Методы производства/Скотобойни|Скотобойни]], [[grey_food_2_ranch/Методы производства/Стандартные изгороди|Стандартные изгороди]]

### scripted_triggers

- **добавляет** (1): `Grey_RPR_is_active`

### technology/technologies

- **дополняет** (1): [[grey_food_2_ranch/Технологии/Огораживание|Огораживание]]

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `gfx/` | 20 | 3 |
| `localization/` | 22 | 0 |

- **gfx/ поверх ваниль**: `gfx/interface/icons/production_method_icons/large_sheep_ranch.dds`, `gfx/interface/icons/production_method_icons/no_refrigeration.dds`, `gfx/interface/icons/production_method_icons/refrigerated_rail_cars.dds`

**События**: 0 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 2; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
