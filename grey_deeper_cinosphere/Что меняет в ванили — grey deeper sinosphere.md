---
type: reference
description: "Что мод grey deeper sinosphere меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
source: grey_deeper_cinosphere
tags: [grey_deeper_cinosphere, что-меняет]
generated: "v3 graph mods"
paths: [grey_add_alot_of_things/grey_deeper_cinosphere/**]
---
# Что меняет в ванили — grey deeper sinosphere

Снимок `grey_add_alot_of_things/grey_deeper_cinosphere`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `cultures` | 2 | 15 | 0 | 0 | 0 | 0 | 0 |
| `decisions` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `discrimination_traits` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 6 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 12 | 0 | 0 | 0 | 0 | 0 | 0 |

### cultures

- **добавляет** (2): `sino`, `yamatos`
- **заменяет** (15): `ainu`, `hakka`, `han`, `japanese`, `kalmyk`, `korean`, `manchu`, `miao`, `min`, `mongol`, `vietnamese`, `yi`, `yuanzhumin`, `yue`, `zhuang`

### decisions

- **добавляет** (2): `sino_decision`, `yamato_decision`

### discrimination_traits

- **добавляет** (1): `tradition_yamato`

### modifier_type_definitions

- **добавляет** (6): `country_fervor_target_sino_add`, `country_fervor_target_yamatos_add`, `country_sino_cultural_acceptance_add`, `country_yamatos_cultural_acceptance_add`, `state_sino_standard_of_living_add`, `state_yamatos_standard_of_living_add`

### static_modifiers

- **добавляет** (12): `sino_cultural_acceptance_modifier_negative`, `sino_cultural_acceptance_modifier_positive`, `sino_fervor_target_modifier_negative`, `sino_fervor_target_modifier_positive`, `sino_standard_of_living_modifier_negative`, `sino_standard_of_living_modifier_positive`, `yamatos_cultural_acceptance_modifier_negative`, `yamatos_cultural_acceptance_modifier_positive`, `yamatos_fervor_target_modifier_negative`, `yamatos_fervor_target_modifier_positive`, `yamatos_standard_of_living_modifier_negative`, `yamatos_standard_of_living_modifier_positive`

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 1 | 0 |
| `localization/` | 33 | 0 |


**События**: 2 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 3976; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
