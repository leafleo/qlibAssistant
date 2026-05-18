# params 
 {'predict_dates': [{'start': '2026-05-18', 'end': '2026-05-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260518_18 945815370969502541 (Recorders: 4/5)

	Recorder: f4a6e34b68a04a61a85148f6686994c8

		Model: {'id': 'f4a6e34b68a04a61a85148f6686994c8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.095, 'Rank IC': 0.016, 'Rank ICIR': 0.12}, 'data_train_vec': ['2021-05-18', '2025-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.120', 'weight': '0.042'}

	Recorder: 6eaa193af9aa4d9abf47919c8d992edd

		Model: {'id': '6eaa193af9aa4d9abf47919c8d992edd', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.059, 'Rank IC': 0.014, 'Rank ICIR': 0.09}, 'data_train_vec': ['2022-05-18', '2025-05-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.090', 'weight': '0.032'}

	Recorder: a40c3a885b4e46408a167d8d586bf651

		Model: {'id': 'a40c3a885b4e46408a167d8d586bf651', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.092, 'Rank IC': 0.023, 'Rank ICIR': 0.147}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.147', 'weight': '0.052'}

	Recorder: 0969e63b189b4dc6a808b019193c7e08

		Model: {'id': '0969e63b189b4dc6a808b019193c7e08', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.272, 'Rank IC': 0.039, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.232', 'weight': '0.082'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260518_18 539848044828585347 (Recorders: 3/5)

	Recorder: e35402e489b74bb88df4dd77ea1f27cb

		Model: {'id': 'e35402e489b74bb88df4dd77ea1f27cb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.143, 'Rank IC': 0.026, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.203', 'weight': '0.072'}

	Recorder: 0311980ac5c244ec8f8c9504d1d36160

		Model: {'id': '0311980ac5c244ec8f8c9504d1d36160', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.114, 'Rank IC': 0.003, 'Rank ICIR': 0.034}, 'data_train_vec': ['2024-05-18', '2025-11-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.034', 'weight': '0.012'}

	Recorder: 25260ad24ea7401091aa0977c0927c2e

		Model: {'id': '25260ad24ea7401091aa0977c0927c2e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.595, 'Rank IC': 0.048, 'Rank ICIR': 0.277}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.277', 'weight': '0.098'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260518_16 910908918120435711 (Recorders: 2/5)

	Recorder: a572ce6d57d047a98854ac242cc5031d

		Model: {'id': 'a572ce6d57d047a98854ac242cc5031d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.098, 'Rank IC': 0.035, 'Rank ICIR': 0.228}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.228', 'weight': '0.080'}

	Recorder: ed217b4d122b4e11895f5a2a6363997f

		Model: {'id': 'ed217b4d122b4e11895f5a2a6363997f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.393, 'Rank IC': 0.036, 'Rank ICIR': 0.2}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.200', 'weight': '0.071'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260518_16 871035957885358994 (Recorders: 4/5)

	Recorder: 30a8d7bc5a334a39b4cf3513268c163e

		Model: {'id': '30a8d7bc5a334a39b4cf3513268c163e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.027, 'Rank ICIR': 0.241}, 'data_train_vec': ['2021-05-18', '2025-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.241', 'weight': '0.085'}

	Recorder: edc74407b252476ab6d2712762bd2ae2

		Model: {'id': 'edc74407b252476ab6d2712762bd2ae2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.071, 'Rank IC': 0.034, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.304', 'weight': '0.107'}

	Recorder: 6f6529aa63b246d6a5bbea95fa04d70a

		Model: {'id': '6f6529aa63b246d6a5bbea95fa04d70a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.015, 'Rank ICIR': 0.132}, 'data_train_vec': ['2024-05-18', '2025-11-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.132', 'weight': '0.047'}

	Recorder: afb5e8cbf1b6496aad8a6da2991e4325

		Model: {'id': 'afb5e8cbf1b6496aad8a6da2991e4325', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.478, 'Rank IC': 0.044, 'Rank ICIR': 0.27}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.270', 'weight': '0.095'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260518_15 370814188733922350 (Recorders: 2/5)

	Recorder: 3899b7f2b63442d8a6888ced3325551f

		Model: {'id': '3899b7f2b63442d8a6888ced3325551f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.082, 'Rank IC': 0.027, 'Rank ICIR': 0.169}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.169', 'weight': '0.060'}

	Recorder: 28c4370957d64f989d6dcba23bc62da4

		Model: {'id': '28c4370957d64f989d6dcba23bc62da4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.217, 'Rank IC': 0.031, 'Rank ICIR': 0.187}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.187', 'weight': '0.066'}
