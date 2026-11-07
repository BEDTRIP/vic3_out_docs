---
type: concept
description: "Закон «Республика (law_parliamentary_republic)» — BPM 1.13, `law_parliamentary_republic`"
project: vic3
source: bpm
aliases: ["Республика (law_parliamentary_republic)", "Republic", "law_parliamentary_republic"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_parliamentary_republic
paths: [BPM/common/laws/BPM_governance_principles.txt]
replaces: "[[vanilla/Законы/Парламентская республика]]"
---
# Республика (law_parliamentary_republic)

Закон · `law_parliamentary_republic` · `common/laws/BPM_governance_principles.txt:274` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **icon**: `"gfx/interface/icons/law_icons/parliamentary_republic.dds"` → `"gfx/interface/icons/law_icons/presidential_republic.dds"`
- **can_enact**: изменено
- **on_activate**: изменено
- **is_visible**: добавлено
- **modifier**: изменено
- **ai_will_do**: изменено
- **ai_impose_chance**: изменено
- **disallowing_laws**: убрано

## Поля

- **group**: [[bpm/Группы законов/Принципы управления|Принципы управления]]
- **icon**: `gfx/interface/icons/law_icons/presidential_republic.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[bpm/Технологии/Демократия|Демократия]]
- **can_impose**: скрипт, строки 285–296
- **can_enact**: скрипт, строки 298–300
- **on_activate**: скрипт, строки 302–314
- **is_visible**: скрипт, строки 316–318
- **modifier**:
  - `country_bureaucrats_voting_power_add` = `5`
  - `country_legitimacy_govt_total_votes_add` = `10`
  - `country_legitimacy_ideological_incoherence_mult` = `0.25`
  - `state_pop_pol_str_add` = `1`
  - `country_liberal_consciousness_change_add` = `0.05`
  - `country_bpm_labor_consciousness_target_mult` = `-0.35`
- **ai_will_do**: скрипт, строки 329–337
- **ai_enact_weight_modifier**: скрипт, строки 339–346
- **ai_impose_chance**: скрипт, строки 348–373

## Ссылаются

- **Законы** (запрещает закон): [[bpm/Законы/Продвижение абсолютистских ценностей|Продвижение абсолютистских ценностей]]
- **Законы** (открывает закон): [[bpm/Законы/Единственная легальная партия|Единственная легальная партия]], [[bpm/Законы/Правые партии запрещены|Правые партии запрещены]], [[bpm/Законы/Социалистические партии запрещены|Социалистические партии запрещены]], [[bpm/Законы/Только правые партии|Только правые партии]], [[bpm/Законы/Только социалистические партии|Только социалистические партии]], [[bpm/Законы/Только умеренные партии|Только умеренные партии]]
- **Идеологии** (lawgroup_governance_principles: approve): [[bpm/Идеологии/Либеральный республиканец|Либеральный республиканец]], [[bpm/Идеологии/Позитивистское движение|Позитивистское движение]], [[bpm/Идеологии/Радикализм|Радикализм]], [[bpm/Идеологии/Республиканство|Республиканство]], [[bpm/Идеологии/Синдикалист (ideology_syndicalist)|Синдикалист (ideology_syndicalist)]], [[bpm/Идеологии/Социалист|Социалист]], [[bpm/Идеологии/Тридемист|Тридемист]], [[bpm/Идеологии/Умеренный пролетарий|Умеренный пролетарий]]
- **Идеологии** (lawgroup_governance_principles: disapprove): [[bpm/Идеологии/Anarchist Movement|Anarchist Movement]], [[bpm/Идеологии/Авангардизм|Авангардизм]], [[bpm/Идеологии/Анархизм|Анархизм]], [[bpm/Идеологии/Анархо-синдикалист (ideology_anarchist_syndicalist)|Анархо-синдикалист (ideology_anarchist_syndicalist)]], [[bpm/Идеологии/Бонапартист|Бонапартист]], [[bpm/Идеологии/Коммунизм|Коммунизм]], [[bpm/Идеологии/Легитимист|Легитимист]], [[bpm/Идеологии/Монархистское движение|Монархистское движение]], [[bpm/Идеологии/Орлеанист|Орлеанист]], [[bpm/Идеологии/Просвещённый роялизм|Просвещённый роялизм]], [[bpm/Идеологии/Радикальный пролетарий|Радикальный пролетарий]], [[bpm/Идеологии/Роялизм|Роялизм]], [[bpm/Идеологии/Социалистическое движение|Социалистическое движение]], [[bpm/Идеологии/Теократия|Теократия]], [[bpm/Идеологии/Тонхак|Тонхак]], [[bpm/Идеологии/Умеренный монархист|Умеренный монархист]]
- **Идеологии** (lawgroup_governance_principles: neutral): [[bpm/Идеологии/Anti-Proletarian|Anti-Proletarian]], [[bpm/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[bpm/Идеологии/Нигилизм|Нигилизм]], [[bpm/Идеологии/Технократ (ideology_positivist)|Технократ (ideology_positivist)]]
- **Идеологии** (lawgroup_governance_principles: strongly_approve): [[bpm/Идеологии/Радикальное движение|Радикальное движение]], [[bpm/Идеологии/Радикальный республиканец|Радикальный республиканец]]
- **Идеологии** (lawgroup_governance_principles: strongly_disapprove): [[bpm/Идеологии/Абсолютистское движение|Абсолютистское движение]], [[bpm/Идеологии/Радикальный монархист|Радикальный монархист]], [[bpm/Идеологии/Теократ|Теократ]]
