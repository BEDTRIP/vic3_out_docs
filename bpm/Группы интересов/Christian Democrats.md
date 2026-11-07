---
type: concept
description: "Группа интересов «Christian Democrats» — BPM 1.13, `ig_christian_democrats`"
project: vic3
source: bpm
aliases: ["Christian Democrats", "ig_christian_democrats"]
tags: [BPM, группа-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_christian_democrats
paths: [BPM/common/interest_groups/zzzzz_BPM_christian_democrats.txt]
---
# Christian Democrats

Группа интересов · `ig_christian_democrats` · `common/interest_groups/zzzzz_BPM_christian_democrats.txt:1`

## Поля

- **color**: `0.52`, `0.85`, `1.0`
- **texture**: `gfx/interface/icons/ig_icons/christian_democrats.dds`
- **layer**: `revolution_dynamic_rural_folk`
- **index**: `8`
- **ideologies**: [[bpm/Идеологии/Не инициализирован (ideology_nonexistent)|Не инициализирован (ideology_nonexistent)]]
- **character_ideologies**: [[bpm/Идеологии/Центрист|Центрист]], [[bpm/Идеологии/Протекционист|Протекционист]], [[bpm/Идеологии/Суверенизм (ideology_sovereignist_leader)|Суверенизм (ideology_sovereignist_leader)]], [[bpm/Идеологии/Либерал-демократ|Либерал-демократ]], [[bpm/Идеологии/Реформы|Реформы]]
- **enable**:
  - `always` = `yes`
- **priority_cultures**: пусто
- **on_enable**: скрипт, строки 28–48
- **on_character_ig_membership**: скрипт, строки 50–69
- **on_disable**: пусто
- **pop_potential**: скрипт, строки 73–91
- **pop_weight**: скрипт, строки 93–657
- **monarch_weight**:
  - `value` = `0.5`
- **agitator_weight**: скрипт, строки 663–672
- **commander_weight**:
  - `value` = `1.0`
  - `multiply` = `bpm_commander_assignment_from_laws_factor`
- **executive_weight**: скрипт, строки 679–687
- **noble_chance**:
  - `value` = `0.2`
- **female_commander_chance**:
  - `value` = `1.0`
  - `multiply` = `bpm_female_commander_spawn_chance`
- **female_politician_chance**:
  - `value` = `1.0`
  - `multiply` = `bpm_female_character_spawn_chance`
- **female_agitator_chance**:
  - `value` = `1.0`
  - `multiply` = `bpm_female_character_spawn_chance`
- **female_executive_chance**:
  - `value` = `1.0`
  - `multiply` = `bpm_female_character_spawn_chance`
- **commander_leader_chance**: скрипт, строки 715–727
