---
type: concept
description: "Вид компании «Société française des charbonnages du Tonkin» — VC 1.13, `company_societe_francaise_charbonnages_du_tonkin`"
project: vic3
source: vc
aliases: ["Société française des charbonnages du Tonkin", "company_societe_francaise_charbonnages_du_tonkin"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_societe_francaise_charbonnages_du_tonkin
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/Société française des charbonnages du Tonkin]]"
---
# Société française des charbonnages du Tonkin

Вид компании · `company_societe_francaise_charbonnages_du_tonkin` · `common/company_types/joi_companies.txt:7868`

## Отличия от ваниль

- **category**: добавлено
- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **prestige_goods_trigger**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_societe_francaise_charbonnages_du_tonkin.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **category**: `bureaucrat_owned`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`, `STATE_TONKIN`
- **building_types**: [[vc/Здания/Угольные шахты|Угольные шахты]], [[vc/Здания/Лесозаготовки|Лесозаготовки]], [[vanilla/Здания/Порты|Порты]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: `prestige_good_generic_merchant_marine`
- **prestige_goods_trigger**: скрипт, строки 7893–7898
- **potential**: скрипт, строки 7900–7902
- **attainable**: скрипт, строки 7904–7912
- **possible**: скрипт, строки 7914–7925
- **prosperity_modifier**:
  - `state_birth_rate_mult` = `0.1`
  - `goods_output_coal_mult` = `0.1` → [[vanilla/Товары/Уголь|Уголь]]
  - `goods_output_hardwood_mult` = `0.1` → [[vanilla/Товары/Твёрдая древесина|Твёрдая древесина]]
- **ai_will_do**: скрипт, строки 7933–7938
- **ai_construction_targets**: скрипт, строки 7940–7947
- **ai_weight**: скрипт, строки 7949–7951
