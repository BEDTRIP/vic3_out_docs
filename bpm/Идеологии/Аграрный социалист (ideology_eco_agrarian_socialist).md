---
type: concept
description: "Идеология «Аграрный социалист (ideology_eco_agrarian_socialist)» — BPM 1.13, `ideology_eco_agrarian_socialist`"
project: vic3
audience: agent
source: bpm
aliases: ["Аграрный социалист (ideology_eco_agrarian_socialist)", "Agrarian Socialist", "ideology_eco_agrarian_socialist"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_eco_agrarian_socialist
paths: [BPM/common/ideologies/bpm_eco_ig_ideologies.txt]
---
# Аграрный социалист (ideology_eco_agrarian_socialist)

Идеология · `ideology_eco_agrarian_socialist` · `common/ideologies/bpm_eco_ig_ideologies.txt:274`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/eco_ideology/agrarian_socialist.dds`
- **priority**: `1000`
- **lawgroup_economic_system**:
  - [[bpm/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[bpm/Законы/Интервенционизм|Интервенционизм]] = `disapprove`
  - [[bpm/Законы/Аграрность|Аграрность]] = `approve`
  - [[bpm/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[bpm/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_disapprove`
  - [[bpm/Законы/Кооперативное владение|Кооперативное владение]] = `approve`
  - [[bpm/Законы/Командная экономика|Командная экономика]] = `disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_disapprove`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `approve`
  - [[bpm/Законы/Изоляционизм|Изоляционизм]] = `neutral`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[bpm/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[bpm/Законы/Арендаторы|Арендаторы]] = `strongly_disapprove`
  - [[bpm/Законы/Крестьянское хозяйство|Крестьянское хозяйство]] = `approve`
  - [[bpm/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `disapprove`
  - [[bpm/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_approve`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `neutral`
  - [[bpm/Законы/Крестьянский налог|Крестьянский налог]] = `strongly_disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `strongly_disapprove`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
- **lawgroup_slavery**:
  - [[bpm/Законы/Запрет рабства|Запрет рабства]] = `neutral`
  - [[bpm/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[bpm/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
  - [[bpm/Законы/Унаследованное рабство|Унаследованное рабство]] = `strongly_disapprove`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `strongly_disapprove`
- **lawgroup_repeatable_economy**:
  - [[bpm/Законы/Экономическая либерализация|Экономическая либерализация]] = `disapprove`
  - [[bpm/Законы/Сельскохозяйственные инвестиции|Сельскохозяйственные инвестиции]] = `strongly_approve`
  - [[bpm/Законы/Крестьянская повинность|Крестьянская повинность]] = `strongly_disapprove`
  - [[bpm/Законы/Общественные работы|Общественные работы]] = `neutral`
  - [[bpm/Законы/Принудительная индустриализация|Принудительная индустриализация]] = `strongly_disapprove`
