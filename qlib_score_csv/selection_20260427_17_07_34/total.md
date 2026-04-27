# params 
 {'predict_dates': [{'start': '2026-04-27', 'end': '2026-04-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260427_16 176594049179105972 (Recorders: 2/5)

	Recorder: bdb93489f35f4cceba1a605028c54154

		Model: {'id': 'bdb93489f35f4cceba1a605028c54154', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.045, 'Rank IC': 0.027, 'Rank ICIR': 0.161}, 'data_train_vec': ['2023-04-27', '2025-07-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.161', 'weight': '0.098'}

	Recorder: 732dbce90c3341569abc8dd8e704d2a2

		Model: {'id': '732dbce90c3341569abc8dd8e704d2a2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.154, 'Rank IC': 0.003, 'Rank ICIR': 0.02}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.020', 'weight': '0.012'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260427_16 299503572312477599 (Recorders: 3/5)

	Recorder: 2b4d788c2de442818e394344bd545d1e

		Model: {'id': '2b4d788c2de442818e394344bd545d1e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.048, 'Rank IC': 0.03, 'Rank ICIR': 0.211}, 'data_train_vec': ['2023-04-27', '2025-07-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.211', 'weight': '0.129'}

	Recorder: 1b6e0fae030742ceb35752bc3968b21b

		Model: {'id': '1b6e0fae030742ceb35752bc3968b21b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.057, 'Rank IC': 0.015, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.121', 'weight': '0.074'}

	Recorder: 3e124617a26e440eade78ce8f07dec56

		Model: {'id': '3e124617a26e440eade78ce8f07dec56', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.24, 'Rank IC': 0.021, 'Rank ICIR': 0.136}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.136', 'weight': '0.083'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260427_14 705612809485152972 (Recorders: 3/5)

	Recorder: b03ff0b5e410474682dd4e8f09c3bedd

		Model: {'id': 'b03ff0b5e410474682dd4e8f09c3bedd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.068, 'Rank IC': 0.042, 'Rank ICIR': 0.246}, 'data_train_vec': ['2023-04-27', '2025-07-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.246', 'weight': '0.150'}

	Recorder: c5577474b61e416c9f19ed4ade4137ed

		Model: {'id': 'c5577474b61e416c9f19ed4ade4137ed', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.087, 'Rank IC': 0.013, 'Rank ICIR': 0.116}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.116', 'weight': '0.071'}

	Recorder: 41d880b00afd4ea4a047eb8e78e68398

		Model: {'id': '41d880b00afd4ea4a047eb8e78e68398', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.167, 'Rank IC': 0.01, 'Rank ICIR': 0.055}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.055', 'weight': '0.034'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260427_14 387509995768092866 (Recorders: 2/5)

	Recorder: c62c4616d2fb45e488a5454159e80034

		Model: {'id': 'c62c4616d2fb45e488a5454159e80034', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.009, 'Rank ICIR': 0.072}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.072', 'weight': '0.044'}

	Recorder: a2f8d66dca5146e0a3ed3dfec10a639f

		Model: {'id': 'a2f8d66dca5146e0a3ed3dfec10a639f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.457, 'Rank IC': 0.032, 'Rank ICIR': 0.223}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.223', 'weight': '0.136'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260427_14 562780001467336365 (Recorders: 2/5)

	Recorder: 74daf7769f1b4612b7a65e8b4d0b3909

		Model: {'id': '74daf7769f1b4612b7a65e8b4d0b3909', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.081, 'Rank IC': 0.029, 'Rank ICIR': 0.265}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.265', 'weight': '0.162'}

	Recorder: 696d1306e9a445d2ab194dec149f529f

		Model: {'id': '696d1306e9a445d2ab194dec149f529f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.002, 'Rank ICIR': 0.012}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.012', 'weight': '0.007'}
