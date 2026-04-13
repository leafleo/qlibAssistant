# params 
 {'predict_dates': [{'start': '2026-04-13', 'end': '2026-04-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260413_16 648955057138141605 (Recorders: 3/5)

	Recorder: 749fd42bf5744538bdd2b6473785db7c

		Model: {'id': '749fd42bf5744538bdd2b6473785db7c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.28, 'Rank IC': 0.046, 'Rank ICIR': 0.316}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.316', 'weight': '0.089'}

	Recorder: 9d4ccf4ef775420384f280b9da574cd9

		Model: {'id': '9d4ccf4ef775420384f280b9da574cd9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.224, 'Rank IC': 0.051, 'Rank ICIR': 0.411}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.411', 'weight': '0.115'}

	Recorder: 9e342872eade4758a9f229fb62c22711

		Model: {'id': '9e342872eade4758a9f229fb62c22711', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.362, 'Rank IC': 0.043, 'Rank ICIR': 0.345}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.345', 'weight': '0.097'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260413_16 655684503375230782 (Recorders: 2/5)

	Recorder: fce51beb1eea442a99b11414f87bb92d

		Model: {'id': 'fce51beb1eea442a99b11414f87bb92d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.108, 'Rank IC': 0.017, 'Rank ICIR': 0.141}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.141', 'weight': '0.040'}

	Recorder: 8357d66767124dca8a16b19a73ece1d1

		Model: {'id': '8357d66767124dca8a16b19a73ece1d1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.203, 'Rank IC': 0.036, 'Rank ICIR': 0.223}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.223', 'weight': '0.063'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260413_14 760105257771405141 (Recorders: 4/5)

	Recorder: 41541078564640c6b45e6c7ec205cc4f

		Model: {'id': '41541078564640c6b45e6c7ec205cc4f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.031, 'Rank IC': 0.023, 'Rank ICIR': 0.134}, 'data_train_vec': ['2021-04-13', '2025-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.134', 'weight': '0.038'}

	Recorder: 6c74160eeb944674b6d90691551a23ce

		Model: {'id': '6c74160eeb944674b6d90691551a23ce', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.097, 'Rank IC': 0.049, 'Rank ICIR': 0.29}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.290', 'weight': '0.081'}

	Recorder: 1e1e5414e93842948ee8715cbe9aec2a

		Model: {'id': '1e1e5414e93842948ee8715cbe9aec2a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.117, 'Rank IC': 0.021, 'Rank ICIR': 0.172}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.172', 'weight': '0.048'}

	Recorder: 6d437971a9514297ae3afeb76c6d0e6f

		Model: {'id': '6d437971a9514297ae3afeb76c6d0e6f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.126, 'Rank IC': 0.016, 'Rank ICIR': 0.09}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.090', 'weight': '0.025'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260413_14 289379134552827521 (Recorders: 4/5)

	Recorder: 81a1b801b22047489eff92e58519098b

		Model: {'id': '81a1b801b22047489eff92e58519098b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.063, 'Rank IC': 0.018, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-04-13', '2025-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.160', 'weight': '0.045'}

	Recorder: 1e867f507b604f5d90a70c0a5fa0a40b

		Model: {'id': '1e867f507b604f5d90a70c0a5fa0a40b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.1, 'Rank IC': 0.037, 'Rank ICIR': 0.321}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.321', 'weight': '0.090'}

	Recorder: 733762bd85824f25be9883b78b5f3c17

		Model: {'id': '733762bd85824f25be9883b78b5f3c17', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.115, 'Rank IC': 0.02, 'Rank ICIR': 0.172}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.172', 'weight': '0.048'}

	Recorder: 8c26fe85df3f466bb26e22117df24cba

		Model: {'id': '8c26fe85df3f466bb26e22117df24cba', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.2, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.138', 'weight': '0.039'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260413_14 427862702384808712 (Recorders: 3/5)

	Recorder: 4f589cf17b6d4bdfa959f5addf70e306

		Model: {'id': '4f589cf17b6d4bdfa959f5addf70e306', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.124, 'Rank IC': 0.037, 'Rank ICIR': 0.226}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.226', 'weight': '0.063'}

	Recorder: 1c9351da66594eefbb3adeeea8aca361

		Model: {'id': '1c9351da66594eefbb3adeeea8aca361', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.161, 'Rank IC': 0.041, 'Rank ICIR': 0.351}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.351', 'weight': '0.098'}

	Recorder: 4438310b33de4ac8a8d79e2c397f1e7d

		Model: {'id': '4438310b33de4ac8a8d79e2c397f1e7d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.121, 'Rank IC': 0.012, 'Rank ICIR': 0.076}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.076', 'weight': '0.021'}
