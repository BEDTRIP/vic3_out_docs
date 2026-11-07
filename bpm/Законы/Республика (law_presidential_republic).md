---
type: concept
description: "Закон «Республика (law_presidential_republic)» — BPM 1.13, `law_presidential_republic`"
project: vic3
source: bpm
aliases: ["Республика (law_presidential_republic)", "Republic", "law_presidential_republic"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_presidential_republic
paths: [BPM/common/laws/BPM_governance_principles.txt]
replaces: "[[vanilla/Законы/Президентская республика]]"
---
# Республика (law_presidential_republic)

Закон · `law_presidential_republic` · `common/laws/BPM_governance_principles.txt:141` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **is_visible**: добавлено
- **on_activate**: изменено
- **modifier**: изменено
- **ai_will_do**: изменено
- **ai_enact_weight_modifier**: изменено
- **ai_impose_chance**: изменено
- **can_enact**: убрано

## Поля

- **group**: [[bpm/Группы законов/Принципы управления|Принципы управления]]
- **icon**: `gfx/interface/icons/law_icons/presidential_republic.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[bpm/Технологии/Демократия|Демократия]]
- **can_impose**: скрипт, строки 152–163
- **is_visible**: скрипт, строки 165–169
- **on_activate**: скрипт, строки 171–189
- **modifier**:
  - `country_bureaucrats_voting_power_add` = `5`
  - `country_authority_add` = `100`
  - `country_legitimacy_ideological_incoherence_mult` = `0.25`
  - `state_pop_pol_str_add` = `1`
  - `country_liberal_consciousness_change_add` = `0.05`
  - `country_bpm_labor_consciousness_target_mult` = `-0.35`
- **ai_will_do**: скрипт, строки 220–228
- **ai_enact_weight_modifier**: скрипт, строки 230–244
- **ai_impose_chance**: скрипт, строки 246–271

## Ссылаются

- **Законы** (запрещает закон): [[bpm/Законы/Продвижение абсолютистских ценностей|Продвижение абсолютистских ценностей]]
- **Законы** (открывает закон): [[bpm/Законы/Единственная легальная партия|Единственная легальная партия]], [[bpm/Законы/Правые партии запрещены|Правые партии запрещены]], [[bpm/Законы/Социалистические партии запрещены|Социалистические партии запрещены]], [[bpm/Законы/Только правые партии|Только правые партии]], [[bpm/Законы/Только социалистические партии|Только социалистические партии]], [[bpm/Законы/Только умеренные партии|Только умеренные партии]]
- **Идеологии** (lawgroup_governance_principles: approve): [[bpm/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[bpm/Идеологии/Либеральный республиканец|Либеральный республиканец]], [[bpm/Идеологии/Радикализм|Радикализм]], [[bpm/Идеологии/Республиканство|Республиканство]], [[bpm/Идеологии/Синдикалист (ideology_syndicalist)|Синдикалист (ideology_syndicalist)]], [[bpm/Идеологии/Социалист|Социалист]], [[bpm/Идеологии/Технократ (ideology_positivist)|Технократ (ideology_positivist)]]
- **Идеологии** (lawgroup_governance_principles: disapprove): [[bpm/Идеологии/Anarchist Movement|Anarchist Movement]], [[bpm/Идеологии/Авангардизм|Авангардизм]], [[bpm/Идеологии/Анархизм|Анархизм]], [[bpm/Идеологии/Анархо-синдикалист (ideology_anarchist_syndicalist)|Анархо-синдикалист (ideology_anarchist_syndicalist)]], [[bpm/Идеологии/Коммунизм|Коммунизм]], [[bpm/Идеологии/Легитимист|Легитимист]], [[bpm/Идеологии/Монархистское движение|Монархистское движение]], [[bpm/Идеологии/Просвещённый роялизм|Просвещённый роялизм]], [[bpm/Идеологии/Радикальный пролетарий|Радикальный пролетарий]], [[bpm/Идеологии/Роялизм|Роялизм]], [[bpm/Идеологии/Социалистическое движение|Социалистическое движение]], [[bpm/Идеологии/Теократия|Теократия]], [[bpm/Идеологии/Умеренный монархист|Умеренный монархист]]
- **Идеологии** (lawgroup_governance_principles: neutral): [[bpm/Идеологии/Anti-Proletarian|Anti-Proletarian]], [[bpm/Идеологии/Бонапартист|Бонапартист]], [[bpm/Идеологии/Нигилизм|Нигилизм]], [[bpm/Идеологии/Орлеанист|Орлеанист]], [[bpm/Идеологии/Тонхак|Тонхак]], [[bpm/Идеологии/Умеренный пролетарий|Умеренный пролетарий]]
- **Идеологии** (lawgroup_governance_principles: strongly_approve): [[bpm/Идеологии/Отменить монархию!|Отменить монархию!]], [[bpm/Идеологии/Позитивистское движение|Позитивистское движение]], [[bpm/Идеологии/Радикальное движение|Радикальное движение]], [[bpm/Идеологии/Радикальный республиканец|Радикальный республиканец]], [[bpm/Идеологии/Тридемист|Тридемист]]
- **Идеологии** (lawgroup_governance_principles: strongly_disapprove): [[bpm/Идеологии/Абсолютистское движение|Абсолютистское движение]], [[bpm/Идеологии/Радикальный монархист|Радикальный монархист]], [[bpm/Идеологии/Теократ|Теократ]]
