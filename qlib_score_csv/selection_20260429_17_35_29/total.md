# params 
 {'predict_dates': [{'start': '2026-04-29', 'end': '2026-04-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260429_17 577206786305332768 (Recorders: 2/5)

	Recorder: 63d50d0c44554b30a3bb39485d27c70b

		Model: {'id': '63d50d0c44554b30a3bb39485d27c70b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.06, 'Rank IC': 0.014, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.142', 'weight': '0.090'}

	Recorder: 3544bafda17d48299a74b4f5399affa3

		Model: {'id': '3544bafda17d48299a74b4f5399affa3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.185, 'Rank IC': 0.009, 'Rank ICIR': 0.056}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.056', 'weight': '0.036'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260429_17 525929058892667500 (Recorders: 2/5)

	Recorder: 2af9992623be43b5be408f00c68a75a2

		Model: {'id': '2af9992623be43b5be408f00c68a75a2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.082, 'Rank IC': 0.012, 'Rank ICIR': 0.111}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.111', 'weight': '0.071'}

	Recorder: d63cefbadb21404099a3080cd6012cea

		Model: {'id': 'd63cefbadb21404099a3080cd6012cea', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.063, 'ICIR': 0.543, 'Rank IC': 0.031, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.232', 'weight': '0.148'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260429_14 862830969351527885 (Recorders: 3/5)

	Recorder: c9765c0b27324896bf4d2d5953c86fd2

		Model: {'id': 'c9765c0b27324896bf4d2d5953c86fd2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.035, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-04-29', '2025-07-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.203', 'weight': '0.129'}

	Recorder: 154ca7a30516405fb1d925907bab5d78

		Model: {'id': '154ca7a30516405fb1d925907bab5d78', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.074, 'Rank IC': 0.005, 'Rank ICIR': 0.047}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.047', 'weight': '0.030'}

	Recorder: b60b7d5cfb2f478c9c65c137e51eb350

		Model: {'id': 'b60b7d5cfb2f478c9c65c137e51eb350', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.252, 'Rank IC': 0.01, 'Rank ICIR': 0.065}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.065', 'weight': '0.041'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260429_14 591914103478609744 (Recorders: 2/5)

	Recorder: 57086b563dbc4b628337406bff797d45

		Model: {'id': '57086b563dbc4b628337406bff797d45', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.031, 'Rank IC': 0.01, 'Rank ICIR': 0.084}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.084', 'weight': '0.053'}

	Recorder: fbb24806c4fb4bccaeefa7c3770085a8

		Model: {'id': 'fbb24806c4fb4bccaeefa7c3770085a8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.626, 'Rank IC': 0.042, 'Rank ICIR': 0.342}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.342', 'weight': '0.218'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260429_14 461369533133494227 (Recorders: 2/5)

	Recorder: 296f44e3c6fb469f9a202e0e510f2933

		Model: {'id': '296f44e3c6fb469f9a202e0e510f2933', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.06, 'Rank IC': 0.02, 'Rank ICIR': 0.177}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.177', 'weight': '0.113'}

	Recorder: ed22e6d8bda84055992746b91d53e74e

		Model: {'id': 'ed22e6d8bda84055992746b91d53e74e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.188, 'Rank IC': 0.014, 'Rank ICIR': 0.113}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.113', 'weight': '0.072'}
