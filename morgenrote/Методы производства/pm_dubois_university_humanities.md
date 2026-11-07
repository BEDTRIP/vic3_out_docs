---
type: concept
description: "Метод производства «pm_dubois_university_humanities» — Morgenröte 1.13, `pm_dubois_university_humanities`"
project: vic3
audience: agent
source: morgenrote
aliases: ["pm_dubois_university_humanities"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_dubois_university_humanities
paths: [Morgenrote/common/production_methods/mr_science_dubois_production_methods.txt]
---
# pm_dubois_university_humanities

Метод производства · `pm_dubois_university_humanities` · `common/production_methods/mr_science_dubois_production_methods.txt:289`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/dubois_university_humanities_pm.dds`
- **unlocking_technologies**: [[morgenrote/Технологии/Антикварианизм|Антикварианизм]]
- **country_modifiers**:
  - **unscaled**:
    - `country_academics_decorative_can_promote_humanities_boolean` = `yes`
    - `country_academics_decorative_humanities_experience_boost_boolean` = `yes`
  - **level_scaled**:
    - `country_academics_decorative_excavation_add` = `0.02`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_manzoni_prints_add` = `2` → [[morgenrote/Товары/Газеты и книги|Газеты и книги]]
- **timed_modifiers**: `pm_dubois_academic_confusion_modifier`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Академическая специализация|Академическая специализация]]
