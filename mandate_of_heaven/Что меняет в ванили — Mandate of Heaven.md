---
type: reference
description: "Что мод Mandate of Heaven меняет в ванили 1.15: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: mandate_of_heaven
tags: [mandate_of_heaven, что-меняет]
generated: "v3 graph mods"
paths: [for addon/Mandate of Heaven/**]
---
# Что меняет в ванили — Mandate of Heaven

Снимок `for addon/Mandate of Heaven`, сравнение с ваниль 1.15. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `achievements` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `ai_strategies` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `amendments` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `buildings` | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
| `character_roles` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |
| `character_templates` | 103 | 3 | 2 | 0 | 0 | 0 | 0 |
| `coat_of_arms` | 69 | 7 | 0 | 0 | 0 | 0 | 0 |
| `company_types` | 10 | 1 | 0 | 0 | 0 | 0 | 0 |
| `country_creation` | 7 | 3 | 2 | 0 | 0 | 0 | 0 |
| `country_definitions` | 10 | 11 | 2 | 0 | 0 | 0 | 0 |
| `country_formation` | 1 | 0 | 1 | 0 | 0 | 0 | 0 |
| `cultures` | 0 | 1 | 4 | 0 | 0 | 0 | 0 |
| `customizable_localization` | 14 | 0 | 0 | 0 | 0 | 0 | 0 |
| `decisions` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |
| `dna_data` | 56 | 1 | 0 | 0 | 0 | 0 | 0 |
| `dynamic_country_map_colors` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `dynamic_country_names` | 7 | 7 | 1 | 0 | 0 | 0 | 0 |
| `flag_definitions` | 22 | 7 | 5 | 0 | 0 | 0 | 0 |
| `game_concepts` | 5 | 0 | 0 | 0 | 0 | 0 | 0 |
| `game_rules` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `genes` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `geographic_regions` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `government_types` | 5 | 2 | 0 | 0 | 0 | 0 | 0 |
| `ideologies` | 8 | 0 | 1 | 0 | 0 | 0 | 0 |
| `interest_groups` | 0 | 0 | 4 | 0 | 0 | 0 | 0 |
| `journal_entries` | 38 | 4 | 1 | 0 | 0 | 0 | 0 |
| `laws` | 5 | 0 | 2 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 25 | 0 | 0 | 17 | 0 | 0 | 0 |
| `political_movements` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `prestige_goods` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `production_method_groups` | 1 | 0 | 1 | 0 | 0 | 0 | 0 |
| `production_methods` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `religions` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_buttons` | 14 | 2 | 0 | 0 | 0 | 0 | 0 |
| `scripted_effects` | 25 | 0 | 2 | 0 | 0 | 0 | 0 |
| `scripted_guis` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_progress_bars` | 9 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 32 | 0 | 0 | 0 | 0 | 0 | 0 |
| `social_classes` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |
| `social_hierarchies` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `state_traits` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 65 | 0 | 1 | 0 | 0 | 0 | 0 |
| `strategic_regions` | 0 | 0 | 3 | 0 | 0 | 0 | 0 |
| `technology/technologies` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `themes` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `treaty_articles` | 1 | 0 | 2 | 0 | 0 | 0 | 0 |

### achievements

- **добавляет** (4): `achievement_different_routes`, `achievement_dream`, `achievement_white_sun`, `achievement_wuxu_reform`

### ai_strategies

- **заменяет** (1): `ai_strategy_default`

### amendments

- **добавляет** (1): `amendment_chinese_traditional_land_system`

### buildings

- **добавляет** (1): [[mandate_of_heaven/Здания/Old Summer Palace|Old Summer Palace]]
- **заменяет** (1): [[mandate_of_heaven/Здания/Запретный город|Запретный город]]

### character_roles

- **добавляет** (3): `character_role_duke_yansheng`, `character_role_self_strengthening_leader`, `character_role_sun_yatsen`

### character_templates

- **добавляет** (103): `chi_bao_shichen_character_template`, `chi_chang_hsueliang_character_template`, `chi_cheng_biguang_character_template`, `chi_deng_shichang_character_template`, `chi_feng_guifen_character_template`, `chi_guangxu_template`, `chi_guiliang_character_template`, `chi_kong_decheng_character_template`, `chi_kong_fanhao_character_template`, `chi_kong_lingyi_character_template`, `chi_kong_xiangke_character_template`, `chi_lin_hongnian_character_template`, `chi_liu_changyou_character_template`, `chi_liu_kunyi_character_template`, `chi_liu_mingchuan_character_template`, `chi_mianxing_character_template`, `chi_moh_sun_yat_sen_character_template`, `chi_pujie_template`, `chi_qiu_jin_character_template`, `chi_shantao_character_template`, `chi_sheng_xuanhuai_character_template`, `chi_shien_pan_character_template`, `chi_song_jiaoren_character_template`, `chi_soong_chingling_character_template`, `chi_sushun_character_template`, `chi_tongzhi_template`, `chi_weiyuan_character_template`, `chi_wengtonghe_template`, `chi_wu_bingjian_executive_template`, `chi_wu_chongyao_character_template`, `chi_xuantong_template`, `chi_yan_botao_template`, `chi_yan_fu_template`, `chi_yang_du_character_template`, `chi_yicong_character_template`, `chi_yinghe_character_template`, `chi_yixuan_character_template`, `chi_yizhen_character_template`, `chi_yung_wing_character_template`, `chi_zaifeng_character_template`, `chi_zaitao_character_template`, `chi_zaiyi_template`, `chi_zaiyuan_character_template`, `chi_zhang_chaofa_template`, `ecchi_chi_cai_e_character_template`, `ecchi_chi_cai_yuanpei_character_template`, `ecchi_chi_cao_futian_character_template`, `ecchi_chi_chen_duxiu_character_template`, `ecchi_chi_chen_jiongming_character_template`, `ecchi_chi_chiang_kai_shek_character_template`, `ecchi_chi_du_yuesheng_character_template`, `ecchi_chi_duan_qirui_character_template`, `ecchi_chi_feng_guozhang_character_template`, `ecchi_chi_feng_yuxiang_character_template`, `ecchi_chi_gu_hongming_character_template`, `ecchi_chi_hu_shih_character_template`, `ecchi_chi_huang_xing_character_template`, `ecchi_chi_ilibu_character_template`, `ecchi_chi_kang_youwei_character_template`, `ecchi_chi_li_dazhao_character_template`, `ecchi_chi_li_hongzhang_character_template`, `ecchi_chi_li_yuanhong_character_template`, `ecchi_chi_liang_qichao_character_template`, `ecchi_chi_lin_heier_character_template`, `ecchi_chi_lin_huiyin_character_template`, `ecchi_chi_long_yun_character_template`, `ecchi_chi_lu_xun_character_template`, `ecchi_chi_lu_zhengxiang_character_template`, `ecchi_chi_ma_fuxiang_character_template`, `ecchi_chi_mao_zedong_character_template`, `ecchi_chi_qi_baishi_character_template`, `ecchi_chi_ronglu_character_template`, `ecchi_chi_shi_dakai_character_template`, `ecchi_chi_tan_sitong_character_template`, `ecchi_chi_tang_caichang_character_template`, `ecchi_chi_wang_jingwei_character_template`, `ecchi_chi_wang_zebang_character_template`, `ecchi_chi_wellington_koo_character_template`, `ecchi_chi_wenxiang_character_template`, `ecchi_chi_wu_peifu_character_template`, `ecchi_chi_xu_shicang_character_template`, `ecchi_chi_yan_xishan_character_template`, `ecchi_chi_yikuang_character_template`, `ecchi_chi_zhang_decheng_character_template`, `ecchi_chi_zhang_jian_character_template`, `ecchi_chi_zhang_xun_character_template`, `ecchi_chi_zhang_zhidong_character_template`, `ecchi_chi_zhang_zuolin_character_template`, `ecchi_chi_zhao_sanduo_character_template`, `ecchi_chi_zhu_de_character_template`, `ecchi_chi_zuo_zongtang_character_template`, `ecchi_tib_11_dalai_lama_character_template`, `ecchi_tib_12_dalai_lama_character_template`, `ecchi_tib_13_dalai_lama_character_template`, `ecchi_tib_14_dalai_lama_character_template`, `ecchi_tib_dorzhiev_character_template`, `moh_chi_frederick_townsend_ward_character_template`, `moh_lobsang_khyenrab_wangchug_character_template`, `moh_mr_chi_hou_debang_character_template`, `moh_shatra_wangpug_gyalpo_character_template`, `moh_yakub_beg_character_template`, `mori_tokugawa_executive_template`, `yuz_cuqicuq_garuljigulj_character_template`
- **заменяет** (3): `CHI_changling_he`, `CHI_lexing_zhang`, `chi_gong_character_template`
- **дополняет** (2): `CHI_qiying_aisin_gioro`, `chi_daoguang_template`

### coat_of_arms

- **добавляет** (69): `AHU`, `AHU_subject`, `CHI_anguo`, `CHI_facist_subject_JAP`, `CHI_fujian`, `CHI_guojun`, `CHI_han`, `CHI_han_subject`, `CHI_kmt`, `CHI_later_jin`, `CHI_later_jin_subject`, `CHI_liansheng`, `CHI_liansheng_jing`, `CHI_ming`, `CHI_ming_subject`, `CHI_minguo`, `CHI_shibaxing`, `CHI_shun`, `CHI_shun_subject`, `CHI_zhongsu`, `FRS`, `FRS_subject`, `FUJ_subject`, `GANSU`, `GANSU_subject`, `GNG`, `GNG_subject`, `GNG_warlord`, `GUI`, `GUI_subject`, `HBE`, `HBE_subject`, `HKG`, `HKG_subject`, `HKG_subject_CHI_communism`, `HNA`, `HNA_subject`, `KOR_independence`, `LEP`, `MACAU`, `MACAU_subject_CHI_communism`, `MCH_fengtian`, `MCH_subject`, `MGL_yuan`, `MGL_yuan_subject`, `SHA`, `SHANGHAI`, `SHANGHAI_subject`, `SHA_subject`, `SHN`, `SHN_subject`, `SIH`, `SIH_subject`, `TURKISTAN`, `TURKISTAN_republic`, `TUV`, `XIB`, `XIB_subject`, `XIN_warlord`, `YETTESHEHER`, `YUE`, `YUE_kmt`, `YUE_subject`, `YUN`, `YUN_muslim`, `YUN_subject`, `ZHI`, `ZHI_subject`, `sub_CHI_communist`
- **заменяет** (7): `BEI_dictatorship`, `DAI_subject`, `LAN`, `LAN_subject`, `LAN_subject_GBR`, `TIB_republic`, `TPG`

### company_types

- **добавляет** (10): [[mandate_of_heaven/Виды компаний/Changyu|Changyu]], [[mandate_of_heaven/Виды компаний/China Aviation|China Aviation]], [[mandate_of_heaven/Виды компаний/Commercial Press|Commercial Press]], [[mandate_of_heaven/Виды компаний/Ewo Hong|Ewo Hong]], [[mandate_of_heaven/Виды компаний/Fou Foong Flour Mill|Fou Foong Flour Mill]], [[mandate_of_heaven/Виды компаний/Machine Weaving Bureau|Machine Weaving Bureau]], [[mandate_of_heaven/Виды компаний/Peking University|Peking University]], [[mandate_of_heaven/Виды компаний/Sanxin|Sanxin]], [[mandate_of_heaven/Виды компаний/State Grid|State Grid]], [[mandate_of_heaven/Виды компаний/Tongrentang|Tongrentang]]
- **заменяет** (1): [[mandate_of_heaven/Виды компаний/Ланьфан Кунсы|Ланьфан Кунсы]]

### country_creation

- **добавляет** (7): `FUJ`, `GANSU`, `HBE`, `HKG`, `MACAU`, `SHANGHAI`, `TURKISTAN`
- **заменяет** (3): `XIB`, `YUE`, `YUN`
- **дополняет** (2): `MCH`, `SIH`

### country_definitions

- **добавляет** (10): `CCP`, `FUJ`, `GANSU`, `HBE`, `HKG`, `LEP`, `MACAU`, `SHANGHAI`, `TURKISTAN`, `YETTESHEHER`
- **заменяет** (11): `AHU`, `GNG`, `GUI`, `HNA`, `SHA`, `SHN`, `SIH`, `XIB`, `XIN`, `YUZ`, `ZHI`
- **дополняет** (2): `YUE`, `YUN`

### country_formation

- **добавляет** (1): `LEP`
- **дополняет** (1): `CHI`

### cultures

- **заменяет** (1): `manchu`
- **дополняет** (4): `hakka`, `han`, `min`, `yue`

### customizable_localization

- **добавляет** (14): `art_names`, `hui_rebellion_status_nian`, `hui_rebellion_status_nian_sol`, `hui_rebellion_status_yunnan`, `moh_chengsheng_gengzhang_education_status`, `moh_chengsheng_gengzhang_fiscal_status`, `moh_chengsheng_gengzhang_military_status`, `opera_names`, `sexagenary_cycle_branches`, `sexagenary_cycle_stems`, `xinhai_huang`, `xinhai_qiu`, `xinhai_sun`, `xinhai_wang`

### decisions

- **добавляет** (3): `moh_qing_shanhai_pass`, `moh_resume_chengsheng_gengzhang`, `moh_tibet_look_for_new_dalai_lama`

### dna_data

- **добавляет** (56): `dna_mori_tokugawa_the_author`, `ecchi_dna_agvan_dorzhiev`, `ecchi_dna_cai_e`, `ecchi_dna_cai_yuanpei`, `ecchi_dna_cao_futian`, `ecchi_dna_chen_duxiu`, `ecchi_dna_chen_jiongming`, `ecchi_dna_chiang_kai_shek`, `ecchi_dna_cixi`, `ecchi_dna_du_yuesheng`, `ecchi_dna_duan_qirui`, `ecchi_dna_feng_guozhang`, `ecchi_dna_feng_yuxiang`, `ecchi_dna_gu_hongming`, `ecchi_dna_hong_xiuquan`, `ecchi_dna_hu_shih`, `ecchi_dna_huang_xing`, `ecchi_dna_ilibu`, `ecchi_dna_kang_youwei`, `ecchi_dna_khedrup_gyatso`, `ecchi_dna_li_dazhao`, `ecchi_dna_li_hongzhang`, `ecchi_dna_li_yuanhong`, `ecchi_dna_liang_qichao`, `ecchi_dna_lin_heier`, `ecchi_dna_lin_huiyin`, `ecchi_dna_long_yun`, `ecchi_dna_lu_xun`, `ecchi_dna_lu_zhengxiang`, `ecchi_dna_ma_fuxiang`, `ecchi_dna_mao_zedong`, `ecchi_dna_qi_baishi`, `ecchi_dna_ronglu`, `ecchi_dna_shi_dakai`, `ecchi_dna_tan_sitong`, `ecchi_dna_tang_caichang`, `ecchi_dna_thubten_gyatso`, `ecchi_dna_trinley_gyatso`, `ecchi_dna_wang_jingwei`, `ecchi_dna_wang_zebang`, `ecchi_dna_wellington_koo`, `ecchi_dna_wenxiang`, `ecchi_dna_wu_peifu`, `ecchi_dna_xu_shichang`, `ecchi_dna_yan_xishan`, `ecchi_dna_yang_xiuqing`, `ecchi_dna_yikuang`, `ecchi_dna_zhang_jian`, `ecchi_dna_zhang_xun`, `ecchi_dna_zhang_zhidong`, `ecchi_dna_zhang_zuolin`, `ecchi_dna_zhu_de`, `ecchi_dna_zuo_zongtang`, `moh_dna_chi_qiujin`, `moh_dna_chi_tao_shu`, `moh_dna_chi_yixin`
- **заменяет** (1): `dna_sun_yat_sen`

### dynamic_country_map_colors

- **добавляет** (4): `moh_beiyang_monarchy`, `moh_beiyang_presidential_republic`, `moh_han_imperial_china`, `moh_shun_imperial_china`

### dynamic_country_names

- **добавляет** (7): `DAI`, `FUJ`, `GANSU`, `HBE`, `LEP`, `TIB`, `XIB`
- **заменяет** (7): `AHU`, `CHI`, `GNG`, `MCH`, `MGL`, `XIN`, `YUE`
- **дополняет** (1): `YUN`

### flag_definitions

- **добавляет** (22): `AHU`, `CCP`, `FRS`, `FUJ`, `GANSU`, `GNG`, `GUI`, `HBE`, `HKG`, `HNA`, `LEP`, `MACAU`, `SHA`, `SHANGHAI`, `SHN`, `SIH`, `TURKISTAN`, `XIB`, `YETTESHEHER`, `YUE`, `YUN`, `ZHI`
- **заменяет** (7): `@canton_scale_cross_x`, `@canton_scale_cross_y`, `@coa_height`, `@coa_width`, `CHI`, `MCH`, `XIN`
- **дополняет** (5): `BEI`, `DAI`, `DEFAULT`, `KOR`, `MGL`

### game_concepts

- **добавляет** (5): `concept_character_role_duke_yansheng`, `concept_character_role_self_strengthening_leader`, `concept_character_role_sun_yatsen`, `concept_shih_chin_pai`, `concept_yen_chin_pai`

### game_rules

- **добавляет** (1): `qing_explode_at_the_beginning`

### genes

- **заменяет** (1): `special_genes`

### geographic_regions

- **добавляет** (2): `geographic_region_begonia_leaf`, `geographic_region_han_region`

### government_types

- **добавляет** (5): `gov_china_feudal_empire`, `gov_china_feudal_kingdom`, `gov_confucian_theocracy`, `gov_dalai_lama_moh`, `gov_dalai_lama_regent`
- **заменяет** (2): `gov_dalai_lama`, `gov_warlord_state`

### ideologies

- **добавляет** (8): [[mandate_of_heaven/Идеологии/gui_sidebar_a_vast_country_button|gui_sidebar_a_vast_country_button]], [[mandate_of_heaven/Идеологии/Juren|Juren]], [[mandate_of_heaven/Идеологии/Manchu Elitist|Manchu Elitist]], [[mandate_of_heaven/Идеологии/Kuomintang Nationalist|Kuomintang Nationalist]], [[mandate_of_heaven/Идеологии/Reformer|Reformer]], [[mandate_of_heaven/Идеологии/Revolutionary|Revolutionary]], [[mandate_of_heaven/Идеологии/Right Kuomintang Nationalist|Right Kuomintang Nationalist]], [[mandate_of_heaven/Идеологии/Provincial Autonomist|Provincial Autonomist]]
- **дополняет** (1): [[mandate_of_heaven/Идеологии/Коммунизм|Коммунизм]]

### interest_groups

- **дополняет** (4): [[mandate_of_heaven/Группы интересов/Вооружённые силы|Вооружённые силы]], [[mandate_of_heaven/Группы интересов/Интеллигенты|Интеллигенты]], [[mandate_of_heaven/Группы интересов/Мелкие буржуа|Мелкие буржуа]], [[mandate_of_heaven/Группы интересов/Селяне|Селяне]]

### journal_entries

- **добавляет** (38): `je_13_factories`, `je_8_flags`, `je_anti_encirclement`, `je_channel_force_into_valor`, `je_chinese_republic_monarchy`, `je_daoguang_reform_grain`, `je_daoguang_reform_main`, `je_daoguang_reform_mine`, `je_daoguang_reform_opium`, `je_father_of_the_republic`, `je_fra_dai`, `je_gaitu_guiliu`, `je_great_yuan`, `je_guofan`, `je_heavenly_land_system`, `je_hui_rebellion`, `je_incorporate_the_west`, `je_jingzhang_railway`, `je_keju`, `je_moh_chengsheng_gengzhang`, `je_moh_start`, `je_moh_tibet_look_for_new_dalai_lama`, `je_new_culture`, `je_new_dynasty`, `je_opium_communism`, `je_panthay_rebellion`, `je_plague_pandemic`, `je_prince_gong`, `je_reconquest_of_the_west`, `je_self_strengthening`, `je_self_strengthening_diplomacy`, `je_self_strengthening_education`, `je_self_strengthening_industry`, `je_self_strengthening_military`, `je_shih_chin_opium`, `je_wuxu`, `je_xianfeng`, `je_xinhai`
- **заменяет** (4): `je_boxer_rebellion`, `je_opium_obsession`, `je_urbanization_events_1`, `je_warlord_china`
- **дополняет** (1): `je_autocracy`

### laws

- **добавляет** (5): [[mandate_of_heaven/Законы/Heavenly Land System|Heavenly Land System]], [[mandate_of_heaven/Законы/Imperial Examination System|Imperial Examination System]], [[mandate_of_heaven/Законы/Night Watchmen|Night Watchmen]], [[mandate_of_heaven/Законы/Provincial Autonomy|Provincial Autonomy]], [[mandate_of_heaven/Законы/Zhou Ritual System|Zhou Ritual System]]
- **дополняет** (2): [[mandate_of_heaven/Законы/Кантонская система|Кантонская система]], [[mandate_of_heaven/Законы/Теократия|Теократия]]

### modifier_type_definitions

- **добавляет** (1): `state_taoism_standard_of_living_add`

### on_actions

- **добавляет** (25): `historical_agitators_yearly_events_moh`, `moh_agitator_monthly_events`, `moh_chengsheng_gengzhang_after_opium_war`, `moh_chengsheng_gengzhang_monthly_offer`, `moh_chengsheng_gengzhang_track_opium_play`, `moh_communism_monthly_events`, `moh_communism_war_battle_score`, `moh_handle_xib_released`, `moh_hui_character_creation`, `moh_ladakh_defeat_report`, `moh_linzexu`, `moh_monthly_events`, `moh_on_character_death`, `moh_on_revolution_start`, `moh_opening_explode`, `moh_qing_monarchy_on_heir_born_events`, `moh_random_yearly_events`, `moh_reconcile_opium_wars_resolution`, `moh_savage_land`, `moh_self_strengthening_character_creation`, `moh_self_strengthening_war`, `moh_sunyatsen_je`, `moh_track_opening_ladakh_war`, `moh_xinjiang_monthly_events`, `qing_monarchy_half_yearly_events`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (17): `on_battle_won`, `on_character_creation`, `on_character_death`, `on_country_released_as_independent`, `on_country_released_as_own_subject`, `on_diplomatic_play_started`, `on_empty_battle_won`, `on_game_started_after_lobby`, `on_half_yearly_pulse_character`, `on_half_yearly_pulse_country`, `on_heir_born`, `on_lost_war`, `on_monthly_pulse_country`, `on_revolution_start`, `on_wargoal_enforced`, `on_won_war`, `on_yearly_pulse_country`

### political_movements

- **добавляет** (1): `movement_wuxu`

### prestige_goods

- **добавляет** (1): `prestige_bicycle_flour`

### production_method_groups

- **добавляет** (1): [[mandate_of_heaven/Группы методов/Old Summer Palace|Old Summer Palace]]
- **дополняет** (1): [[mandate_of_heaven/Группы методов/Производство предметов роскоши|Производство предметов роскоши]]

### production_methods

- **добавляет** (2): [[mandate_of_heaven/Методы производства/Traditional Kiln|Traditional Kiln]], [[mandate_of_heaven/Методы производства/Old Summer Palace|Old Summer Palace]]

### religions

- **добавляет** (1): `taoism`

### script_values

- **добавляет** (2): `current_year_dizhi_mod`, `current_year_tiangan_mod`

### scripted_buttons

- **добавляет** (14): `china_han_button`, `china_later_jin_button`, `china_ming_button`, `china_qing_button`, `china_shun_button`, `dismissed_officials_petition_button`, `gaitu_guiliu_button_1`, `gaitu_guiliu_button_2`, `je_guofan_button`, `legalize_opium_button`, `print_reformer_newspaper_button`, `steady_advancement_button`, `support_shih_chin_pai_button`, `support_yen_chin_pai_button`
- **заменяет** (2): `ban_opium_button`, `unban_opium_button`

### scripted_effects

- **добавляет** (25): `STATE_ALTAI_state_name_assign`, `STATE_KIRGHIZIA_state_name_assign`, `STATE_SHAOZHOU_state_name_assign`, `STATE_TUVA_state_name_assign`, `add_shih_chin_10`, `add_shih_chin_5`, `add_yen_chin_10`, `add_yen_chin_5`, `assign_state_name_region_central_asia`, `assign_state_name_region_west_siberia`, `divide_kmt`, `form_new_dynasty`, `moh_generate_duke_yansheng`, `moh_random_opera_name`, `moh_refresh_rebellion_risk`, `moh_setup_communist_china_laws`, `remove_8_banners`, `sun_yatsen_goto`, `warlord_610_bei`, `warlord_610_chi`, `warlord_setup_countries`, `warlord_setup_countries_protection`, `warlord_setup_effect_laws`, `warlord_setup_effect_ruler`, `warlord_setup_mongolia`
- **дополняет** (2): `assign_state_hub_dynamic_names`, `assign_state_name_region_south_china`

### scripted_guis

- **добавляет** (2): `gui_sidebar_a_vast_country_button`, `moh_missing_cmf_sgui`

### scripted_progress_bars

- **добавляет** (9): `daoguang_opium_progress_bar`, `gong_progress_bar`, `new_culture_anarchist_progress_bar`, `new_culture_communist_progress_bar`, `new_culture_monarchy_progress_bar`, `new_culture_presidential_autocracy_progress_bar`, `new_culture_united_provinces_progress_bar`, `wuxu_progress_bar`, `xianfeng_progress_bar`

### scripted_triggers

- **добавляет** (32): `community_framework_is_active`, `ideology_moh_kmt_valid_trigger`, `ideology_moh_reformer_valid_trigger`, `ideology_moh_revolutionary_valid_trigger`, `mandate_o_h_is_active`, `moh_chengsheng_gengzhang_can_offer`, `moh_chengsheng_gengzhang_education_reform`, `moh_chengsheng_gengzhang_eligible`, `moh_chengsheng_gengzhang_fiscal_reform`, `moh_chengsheng_gengzhang_military_reform`, `moh_coa_def_nihilist_flag_trigger`, `moh_nian_has_poor_farmers`, `moh_nian_has_struggling_farmers`, `moh_nian_monitored_states_exist`, `moh_nian_rebellion_active`, `moh_nian_rebellion_resolved`, `moh_rebellion_map_active`, `moh_rebellion_map_nian_state`, `moh_rebellion_map_poor_farmers`, `moh_rebellion_map_ready`, `moh_rebellion_map_rebel_controlled`, `moh_rebellion_map_resolved`, `moh_rebellion_map_tracked_state`, `moh_rebellion_map_warning`, `moh_rebellion_map_west_ready`, `moh_rebellion_map_west_state`, `moh_yunnan_monitored_states_exist`, `sun_yatsen_trigger_10`, `sun_yatsen_trigger_15`, `sun_yatsen_trigger_20`, `sun_yatsen_trigger_25`, `sun_yatsen_trigger_30`

### social_classes

- **добавляет** (3): `lower_class_china`, `middle_class_china`, `upper_class_china`

### social_hierarchies

- **добавляет** (1): `china_shinonggongshang_system`

### state_traits

- **добавляет** (4): `state_trait_chieftains`, `state_trait_dragon_rise_land`, `state_trait_great_wall`, `state_trait_savage_land`

### static_modifiers

- **добавляет** (65): `book_campaign_modifier`, `flood_of_pirates`, `focus_on_navy`, `gaitu_guiliu_building_modifier`, `gaitu_guiliu_cooldown_modifier`, `gaitu_guiliu_gov_ig_modifier`, `modifier_13_factories`, `modifier_8_flags`, `modifier_abolish_keju`, `modifier_ban_opium_communism`, `modifier_chi_keju`, `modifier_chi_wuxu`, `modifier_chi_wuxu_stable`, `modifier_chi_xinhai`, `modifier_communist_china_soviet_base_area`, `modifier_conservatism_grow`, `modifier_daoguang`, `modifier_daoguang_failed`, `modifier_father`, `modifier_gaitu_guiliu_success`, `modifier_great_assembly`, `modifier_imperial_art_show`, `modifier_imperial_art_studio`, `modifier_keju_cheat`, `modifier_keju_cheat_person`, `modifier_keju_cheat_punishment`, `modifier_mandate_of_heaven`, `modifier_moh_chengsheng_gengzhang_compensation`, `modifier_moh_chengsheng_gengzhang_compromise`, `modifier_moh_chengsheng_gengzhang_deferred`, `modifier_moh_chengsheng_gengzhang_education`, `modifier_moh_chengsheng_gengzhang_fiscal`, `modifier_moh_chengsheng_gengzhang_force`, `modifier_moh_chengsheng_gengzhang_military`, `modifier_moh_chengsheng_gengzhang_momentum`, `modifier_moh_chengsheng_gengzhang_reformed`, `modifier_moh_chengsheng_gengzhang_unchanged`, `modifier_moh_communist_china_guerilla_warfare`, `modifier_moh_dignified_portrait`, `modifier_moh_silver_plate_portrait`, `modifier_mongol_yuan`, `modifier_official_corruption`, `modifier_opera`, `modifier_opera_expensive`, `modifier_panthay`, `modifier_plague_lockdown`, `modifier_plague_pandemic`, `modifier_plague_relief`, `modifier_self_strengthening`, `modifier_self_strengthening_donate`, `modifier_self_strengthening_donate_character`, `modifier_self_strengthening_success`, `modifier_self_strengthening_success_company`, `modifier_south_great_wall_fixing`, `modifier_support_overseas_chinese`, `modifier_western_incorporation`, `modifier_western_incorporation_failed`, `modifier_wuxu_authority`, `modifier_wuxu_experienced_teacher`, `modifier_xianfeng`, `modifier_xianfeng_failed`, `modifier_yue_customs_taxes_addition`, `opium_wars_addiction_shih_chin_modifier`, `taoism_standard_of_living_modifier_negative`, `taoism_standard_of_living_modifier_positive`
- **дополняет** (1): `modifier_chinese_warlord_era`

### strategic_regions

- **дополняет** (3): `region_north_china`, `region_northeast_asia`, `region_south_china`

### technology/technologies

- **добавляет** (1): [[mandate_of_heaven/Технологии/Chinese Kiln|Chinese Kiln]]

### themes

- **добавляет** (1): `main_menu_image_moh`

### treaty_articles

- **добавляет** (1): `ban_boxer_rebellion`
- **дополняет** (2): `no_tariffs`, `treaty_port`

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 19 | 2 |
| `gui/` | 9 | 1 |
| `gfx/` | 226 | 10 |
| `localization/` | 67 | 0 |
| `map_data/` | 5 | 3 |
| `music/` | 3 | 1 |
| `dlc_metadata/` | 1 | 0 |

- **events/ поверх ваниль**: `events/opium_wars_events.txt`, `events/warlord_china_events.txt`
- **gui/ поверх ваниль**: `gui/frontend/frontend_main.gui`
- **gfx/ поверх ваниль**: `gfx/interface/error_lion.dds`, `gfx/interface/error_manul.dds`, `gfx/interface/illustrations/journal/je_group_illu_qing.dds`, `gfx/map/map_object_data/generated_map_object_locators_city.txt`, `gfx/map/map_object_data/generated_map_object_locators_farm.txt`, `gfx/map/map_object_data/generated_map_object_locators_mine.txt`, `gfx/map/map_object_data/generated_map_object_locators_port.txt`, `gfx/map/map_object_data/generated_map_object_locators_wood.txt`, `gfx/map/spline_network/spline_network.splnet`, `gfx/particles/textures/revolution_intelligentsia_symbol.dds`
- **map_data/ поверх ваниль**: `map_data/default.map`, `map_data/province_terrains.txt`, `map_data/provinces.png`
- **music/ поверх ваниль**: `music/main_themes/music.txt`

**События**: 104 id; с id ваниль — 14 (`historical_agitators.21`, `opium_wars.1`, `opium_wars.2`, `opium_wars.3`, `opium_wars.4`, `opium_wars.5`, `opium_wars.6`, `opium_wars.7`, `opium_wars.8`, `warlord_china_events.100`, `warlord_china_events.101`, `warlord_china_events.110`, `warlord_china_events.200`, `warlord_china_events.301`) — игра оставляет одно, не по порядку модов.

**Локализация** (английская и русская): ключей 2152; в `replace/` — 19; есть у ваниль вне `replace/` — 4 (не действуют: побеждает первый файл).
