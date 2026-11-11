---
type: reference
description: "Что мод grey diplo меняет в ванили 1.15 (снимок мода — 1.13): записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: grey_diplo
tags: [grey_diplo, что-меняет]
generated: "v3 graph mods"
paths: [grey_add_alot_of_things/grey_diplo/**]
---
# Что меняет в ванили — grey diplo

Снимок `grey_add_alot_of_things/grey_diplo` (снимок мода — 1.13), сравнение с ваниль 1.15. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `diplomatic_actions` | 1 | 2 | 0 | 0 | 0 | 0 | 0 |
| `game_concepts` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 2 | 1 | 0 | 0 | 0 | 0 | 0 |
| `treaty_articles` | 0 | 3 | 0 | 0 | 0 | 0 | 0 |

### diplomatic_actions

- **добавляет** (1): `break_truce`
- **заменяет** (2): `trade_states`, `violate_sovereignty`

### game_concepts

- **добавляет** (1): `concept_military_relevance`

### script_values

- **добавляет** (1): `break_truce_cost`

### scripted_triggers

- **добавляет** (2): `Grey_DIS_is_active`, `is_giftable_treaty_article`
- **заменяет** (1): `violate_sovereignty_war_check`

### treaty_articles

- **заменяет** (3): `foreign_investment_rights`, `goods_transfer`, `state_transfer`

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `gfx/` | 1 | 0 |
| `localization/` | 2 | 0 |


**События**: 0 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 14; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
