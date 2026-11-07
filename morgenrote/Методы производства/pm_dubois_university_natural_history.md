---
type: concept
description: "Метод производства «pm_dubois_university_natural_history» — Morgenröte 1.13, `pm_dubois_university_natural_history`"
project: vic3
audience: agent
source: morgenrote
aliases: ["pm_dubois_university_natural_history"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dubois_university_natural_history
paths: [Morgenrote/common/production_methods/mr_science_dubois_production_methods.txt]
---
# pm_dubois_university_natural_history

Метод производства · `pm_dubois_university_natural_history` · `common/production_methods/mr_science_dubois_production_methods.txt:318`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dubois_university_natural_history_pm.dds`
- **unlocking_technologies**: [[morgenrote/Технологии/Геология|Геология]]
- **country_modifiers**:
  - **unscaled**:
    - `country_academics_decorative_can_promote_natural_boolean` = `yes`
    - `country_academics_decorative_natural_experience_boost_boolean` = `yes`
  - **level_scaled**:
    - `country_academics_decorative_natural_history_project_add` = `0.05`
    - `country_academics_decorative_animal_breeding_progress_add` = `0.01`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_manzoni_prints_add` = `2` → [[morgenrote/Товары/Газеты и книги|Газеты и книги]]
- **timed_modifiers**: `pm_dubois_academic_confusion_modifier`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Академическая специализация|Академическая специализация]]
