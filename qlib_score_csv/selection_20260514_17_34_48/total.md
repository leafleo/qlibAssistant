# params 
 {'predict_dates': [{'start': '2026-05-14', 'end': '2026-05-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260514_17 269471247628216080 (Recorders: 3/5)

	Recorder: e49f0d9512fe4bd087a651db01d1b246

		Model: {'id': 'e49f0d9512fe4bd087a651db01d1b246', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.053, 'Rank IC': 0.021, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-05-14', '2025-05-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.138', 'weight': '0.055'}

	Recorder: f35d61b88bc1499d8abd8a960abc582b

		Model: {'id': 'f35d61b88bc1499d8abd8a960abc582b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.138, 'Rank IC': 0.011, 'Rank ICIR': 0.075}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.075', 'weight': '0.030'}

	Recorder: c59448ce57834d2ea8c36ace6fa650d0

		Model: {'id': 'c59448ce57834d2ea8c36ace6fa650d0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.473, 'Rank IC': 0.037, 'Rank ICIR': 0.229}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.229', 'weight': '0.092'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260514_17 191443094077259709 (Recorders: 3/5)

	Recorder: ae33dfd4664948f2a370318b987acf93

		Model: {'id': 'ae33dfd4664948f2a370318b987acf93', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.19, 'Rank IC': 0.027, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-05-14', '2025-08-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.225', 'weight': '0.090'}

	Recorder: 2255a81cb0ee4dd8a939b5f08a49325e

		Model: {'id': '2255a81cb0ee4dd8a939b5f08a49325e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.127, 'Rank IC': 0.006, 'Rank ICIR': 0.057}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.057', 'weight': '0.023'}

	Recorder: 7d92d07464e24ee584c67c0af7422443

		Model: {'id': '7d92d07464e24ee584c67c0af7422443', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.639, 'Rank IC': 0.046, 'Rank ICIR': 0.304}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.304', 'weight': '0.122'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260514_14 190380991933632383 (Recorders: 3/5)

	Recorder: b4533ed51bb94f0a8ecd0277e047217c

		Model: {'id': 'b4533ed51bb94f0a8ecd0277e047217c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.009, 'Rank IC': 0.028, 'Rank ICIR': 0.149}, 'data_train_vec': ['2022-05-14', '2025-05-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.149', 'weight': '0.060'}

	Recorder: 35c2a094a41b46eea27262245f155dd6

		Model: {'id': '35c2a094a41b46eea27262245f155dd6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.122, 'Rank IC': 0.04, 'Rank ICIR': 0.254}, 'data_train_vec': ['2023-05-14', '2025-08-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.254', 'weight': '0.102'}

	Recorder: f9ab5f1ff1e146a9b22628222005763f

		Model: {'id': 'f9ab5f1ff1e146a9b22628222005763f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.074, 'ICIR': 0.45, 'Rank IC': 0.031, 'Rank ICIR': 0.183}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.183', 'weight': '0.073'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260514_14 635465945490866747 (Recorders: 3/5)

	Recorder: 90cb7da24cb641cd881e0175570e621a

		Model: {'id': '90cb7da24cb641cd881e0175570e621a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.021, 'Rank IC': 0.027, 'Rank ICIR': 0.246}, 'data_train_vec': ['2023-05-14', '2025-08-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.246', 'weight': '0.099'}

	Recorder: e1cab61d1a1645c3aedf2e1060fb06a8

		Model: {'id': 'e1cab61d1a1645c3aedf2e1060fb06a8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.076, 'Rank IC': 0.019, 'Rank ICIR': 0.166}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.166', 'weight': '0.067'}

	Recorder: 89d8174cf2e6419d942189f480a29cb6

		Model: {'id': '89d8174cf2e6419d942189f480a29cb6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.528, 'Rank IC': 0.044, 'Rank ICIR': 0.277}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.277', 'weight': '0.111'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260514_14 354927374676030338 (Recorders: 2/5)

	Recorder: d8a8234b90f9418d8258f6e61fce726a

		Model: {'id': 'd8a8234b90f9418d8258f6e61fce726a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.121, 'Rank IC': 0.002, 'Rank ICIR': 0.018}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.018', 'weight': '0.007'}

	Recorder: a48a445a64f7452fa2014b188e0fed9f

		Model: {'id': 'a48a445a64f7452fa2014b188e0fed9f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.489, 'Rank IC': 0.025, 'Rank ICIR': 0.171}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.171', 'weight': '0.069'}
