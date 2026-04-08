# params 
 {'predict_dates': [{'start': '2026-04-08', 'end': '2026-04-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260408_16 461580584524164168 (Recorders: 3/5)

	Recorder: 1960a0e275934941ba996c5c31a9e95b

		Model: {'id': '1960a0e275934941ba996c5c31a9e95b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.141, 'Rank IC': 0.045, 'Rank ICIR': 0.285}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.285', 'weight': '0.087'}

	Recorder: 6e99c1cf300e4d89821afb2802095a8c

		Model: {'id': '6e99c1cf300e4d89821afb2802095a8c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.312, 'Rank IC': 0.035, 'Rank ICIR': 0.296}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.296', 'weight': '0.090'}

	Recorder: e51ccdfb2e66403f954e600abe9d39d9

		Model: {'id': 'e51ccdfb2e66403f954e600abe9d39d9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.144, 'Rank IC': 0.011, 'Rank ICIR': 0.071}, 'data_train_vec': ['2025-04-08', '2026-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.071', 'weight': '0.022'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260408_16 138264669044226796 (Recorders: 1/5)

	Recorder: bd2bc57771a24dab8f12a0c3a75852f0

		Model: {'id': 'bd2bc57771a24dab8f12a0c3a75852f0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.322, 'Rank IC': 0.037, 'Rank ICIR': 0.311}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.311', 'weight': '0.094'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260408_14 674384322559381815 (Recorders: 3/5)

	Recorder: be17861aee8c46e9a5d980c11522c8ae

		Model: {'id': 'be17861aee8c46e9a5d980c11522c8ae', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.023, 'Rank ICIR': 0.133}, 'data_train_vec': ['2021-04-08', '2025-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.133', 'weight': '0.040'}

	Recorder: 1d72cf2b850b467c9b82faeaae121f0a

		Model: {'id': '1d72cf2b850b467c9b82faeaae121f0a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.126, 'Rank IC': 0.054, 'Rank ICIR': 0.323}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.323', 'weight': '0.098'}

	Recorder: a60ab2a300f34159a81157f03dfc5fe3

		Model: {'id': 'a60ab2a300f34159a81157f03dfc5fe3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.384, 'Rank IC': 0.04, 'Rank ICIR': 0.371}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.371', 'weight': '0.113'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260408_14 427695678140372954 (Recorders: 5/5)

	Recorder: 6e90206057544b418890ea15703c901e

		Model: {'id': '6e90206057544b418890ea15703c901e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.111, 'Rank IC': 0.022, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-04-08', '2025-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.183', 'weight': '0.056'}

	Recorder: 355af279a33141adb8d412bcda03a259

		Model: {'id': '355af279a33141adb8d412bcda03a259', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.057, 'Rank IC': 0.025, 'Rank ICIR': 0.212}, 'data_train_vec': ['2022-04-08', '2025-04-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.212', 'weight': '0.064'}

	Recorder: b511c2bb150a4efe81ed2e9fcc7a2f0d

		Model: {'id': 'b511c2bb150a4efe81ed2e9fcc7a2f0d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.153, 'Rank IC': 0.044, 'Rank ICIR': 0.38}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.380', 'weight': '0.115'}

	Recorder: 3ca58f07c81542c3bdb95cd994b18f59

		Model: {'id': '3ca58f07c81542c3bdb95cd994b18f59', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.067, 'Rank IC': 0.011, 'Rank ICIR': 0.092}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.092', 'weight': '0.028'}

	Recorder: bd8123cf57c744fa94bcae34b43cf524

		Model: {'id': 'bd8123cf57c744fa94bcae34b43cf524', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.072, 'Rank IC': 0.006, 'Rank ICIR': 0.036}, 'data_train_vec': ['2025-04-08', '2026-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.036', 'weight': '0.011'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260408_13 331433373984067329 (Recorders: 3/5)

	Recorder: 0bc73ff91231442696c5ecee8faeee60

		Model: {'id': '0bc73ff91231442696c5ecee8faeee60', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.088, 'Rank IC': 0.025, 'Rank ICIR': 0.141}, 'data_train_vec': ['2021-04-08', '2025-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.141', 'weight': '0.043'}

	Recorder: 6b9b2b1b88734a0b921b494e360f5224

		Model: {'id': '6b9b2b1b88734a0b921b494e360f5224', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.032, 'Rank ICIR': 0.189}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.189', 'weight': '0.057'}

	Recorder: e5aa922907d3417aba7a57af9b50f80d

		Model: {'id': 'e5aa922907d3417aba7a57af9b50f80d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.301, 'Rank IC': 0.031, 'Rank ICIR': 0.27}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.270', 'weight': '0.082'}
