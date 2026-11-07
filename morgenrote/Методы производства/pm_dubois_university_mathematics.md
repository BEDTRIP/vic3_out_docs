---
type: concept
description: "Метод производства «pm_dubois_university_mathematics» — Morgenröte 1.13, `pm_dubois_university_mathematics`"
project: vic3
audience: agent
source: morgenrote
aliases: ["pm_dubois_university_mathematics"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dubois_university_mathematics
paths: [Morgenrote/common/production_methods/mr_science_dubois_production_methods.txt]
---
# pm_dubois_university_mathematics

Метод производства · `pm_dubois_university_mathematics` · `common/production_methods/mr_science_dubois_production_methods.txt:348`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dubois_university_natural_technology_pm.dds`
- **unlocking_technologies**: [[morgenrote/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **country_modifiers**:
  - **unscaled**:
    - `country_academics_decorative_can_promote_mathematical_boolean` = `yes`
    - `country_academics_decorative_mathematical_experience_boost_boolean` = `yes`
  - **level_scaled**:
    - `country_academics_decorative_mathematical_project_add` = `0.05`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_manzoni_prints_add` = `2` → [[morgenrote/Товары/Газеты и книги|Газеты и книги]]
- **timed_modifiers**: `pm_dubois_academic_confusion_modifier`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Академическая специализация|Академическая специализация]]
