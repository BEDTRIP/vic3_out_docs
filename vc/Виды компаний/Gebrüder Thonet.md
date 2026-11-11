---
type: concept
description: "Вид компании «Gebrüder Thonet» — VC 1.15, `company_gebruder_thonet`"
project: vic3
audience: agent
source: vc
aliases: ["Gebrüder Thonet", "company_gebruder_thonet"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_gebruder_thonet
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Gebrüder Thonet]]"
---
# Gebrüder Thonet

Вид компании · `company_gebruder_thonet` · `common/company_types/joi_companies.txt:5601`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_gebruder_thonet.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`
- **building_types**: [[vc/Здания/Мебельные фабрики|Мебельные фабрики]], [[vc/Здания/Лесозаготовки|Лесозаготовки]]
- **extension_building_types**: [[vc/Здания/Стеклозаводы|Стеклозаводы]]
- **possible_prestige_goods**: `prestige_good_bentwood_furniture`
- **potential**: скрипт, строки 5622–5625
- **attainable**: скрипт, строки 5627–5635
- **possible**: скрипт, строки 5637–5646
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-petty-bourgeoisie-pop-attraction-mult|interest_group_ig_petty_bourgeoisie_pop_attraction_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-furniture-mult|goods_output_furniture_mult]] = `0.15` → [[vanilla/Товары/Мебель|Мебель]]
- **ai_will_do**: скрипт, строки 5654–5659
- **ai_construction_targets**: скрипт, строки 5661–5668
- **ai_weight**: скрипт, строки 5670–5672
