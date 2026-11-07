---
type: concept
description: "Идеология «Artisans» — BPM 1.13, `ideology_eco_artisan`"
project: vic3
source: bpm
aliases: ["Artisans", "ideology_eco_artisan"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_eco_artisan
paths: [BPM/common/ideologies/bpm_eco_ig_ideologies.txt]
---
# Artisans

Идеология · `ideology_eco_artisan` · `common/ideologies/bpm_eco_ig_ideologies.txt:57`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/eco_ideology/artisan.dds`
- **priority**: `1000`
- **lawgroup_economic_system**:
  - [[bpm/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[bpm/Законы/Интервенционизм|Интервенционизм]] = `strongly_disapprove`
  - [[bpm/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[bpm/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_approve`
  - [[bpm/Законы/Запрет промышленности|Запрет промышленности]] = `neutral`
  - [[bpm/Законы/Кооперативное владение|Кооперативное владение]] = `approve`
  - [[bpm/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `neutral`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `strongly_approve`
  - [[bpm/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
- **lawgroup_land_reform**:
  - [[bpm/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[bpm/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[bpm/Законы/Крестьянское хозяйство|Крестьянское хозяйство]] = `neutral`
  - [[bpm/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `approve`
  - [[bpm/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `neutral`
  - [[bpm/Законы/Крестьянский налог|Крестьянский налог]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `approve`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `disapprove`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_disapprove`
- **lawgroup_slavery**:
  - [[bpm/Законы/Запрет рабства|Запрет рабства]] = `neutral`
  - [[bpm/Законы/Долговое рабство|Долговое рабство]] = `neutral`
  - [[bpm/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
  - [[bpm/Законы/Унаследованное рабство|Унаследованное рабство]] = `disapprove`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `disapprove`
- **lawgroup_repeatable_economy**:
  - [[bpm/Законы/Экономическая либерализация|Экономическая либерализация]] = `strongly_approve`
  - [[bpm/Законы/Сельскохозяйственные инвестиции|Сельскохозяйственные инвестиции]] = `neutral`
  - [[bpm/Законы/Крестьянская повинность|Крестьянская повинность]] = `disapprove`
  - [[bpm/Законы/Общественные работы|Общественные работы]] = `strongly_disapprove`
  - [[bpm/Законы/Принудительная индустриализация|Принудительная индустриализация]] = `strongly_disapprove`
